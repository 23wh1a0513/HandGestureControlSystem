## Hand Gesture Control System

## Overview

A real-time computer vision application that enables users to control mouse movements, scrolling, clicking, and system volume using hand gestures. The project uses MediaPipe for hand tracking, OpenCV for image processing, PyAutoGUI for mouse automation, and Pycaw for volume control.

## Features

* Virtual Mouse Control
* Mouse Click Detection
* Scroll Up/Down Using Gestures
* Real-Time Volume Adjustment
* Hand Landmark Detection with MediaPipe


## Technologies Used

* Python
* OpenCV
* MediaPipe
* NumPy
* PyAutoGUI
* Pycaw

## Gesture Controls

| Gesture                  | Action         |
| ------------------------ | -------------- |
| All Fingers Closed       | Neutral Mode   |
| Index Finger Up          | Scroll Up      |
| Index + Middle Finger Up | Scroll Down    |
| Thumb + Index Finger Up  | Volume Control |
| All Fingers Up           | Cursor Control |

## Installation

```bash
pip install opencv-python mediapipe numpy pyautogui pycaw comtypes
```

## Run the Project

```bash
python main.py
```

Press **Q** to exit.

## Learning Outcomes

* Computer Vision
* Hand Gesture Recognition
* Human-Computer Interaction
* Real-Time Automation Using Python


