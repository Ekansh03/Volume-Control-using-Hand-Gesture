# Gesture Volume Controller

## Overview
The **Gesture Volume Controller** is a Python-based project that allows users to control the system volume using hand gestures. It uses **OpenCV** for video processing, **MediaPipe** for hand tracking, and **PyAutoGUI** to simulate key presses for volume control.

## Features
- **Real-time Gesture Recognition** to detect hand positions using a webcam.
- **Volume Control:** Pointing gestures adjust volume up or down.

## How It Works
- **Detects Hand Landmarks:** Uses MediaPipe to identify the index finger and thumb positions.
- **Gesture-Based Control:** If the index finger is above the thumb, it increases the volume; if below, it decreases the volume.

## Setup
1. **Install Dependencies:**  
   ```bash
   pip install opencv-python-headless mediapipe pyautogui
   ```
2. **Run the Program:**  
   ```bash
   python gesture_volume_controller.py
   ```
3. **Control Volume:** Use pointing gestures to increase or decrease the volume. Press 'q' to quit.

