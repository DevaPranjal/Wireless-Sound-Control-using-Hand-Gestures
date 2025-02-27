# Wireless Sound Control using Hand Gestures

This project implements wireless sound control using hand gestures, built with Python, OpenCV, and Mediapipe. It captures video from a webcam, detects hand landmarks and uses the distance between specific points (thumb and index finger) to control system volume in real time.

## Features
- **Real-time Hand Tracking:** Uses Mediapipe for detecting hand landmarks.
- **Gesture-Based Volume Control:** Adjusts system volume based on hand gesture distance.
- **Visual Feedback:** Displays hand landmarks and volume level on the video feed.

## Prerequisites
- **Python 3.x**
- A webcam (connected and accessible)
- **Operating System:** Windows (for `pycaw` compatibility)
