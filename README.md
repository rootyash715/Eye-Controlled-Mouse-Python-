# Eye-Controlled-Mouse-Python-
Eye Mouse – Control Your Mouse with Just Your Eyes

# Eye-Controlled Mouse (Python)

A lightweight Python project that controls the OS mouse using eye/iris tracking from a webcam. Blink/wink gestures perform left/right clicks. Built with MediaPipe Face Mesh, OpenCV, NumPy and PyAutoGUI.

## Demo
> Add a short animated GIF or short video here showing the cursor following eye movement and wink clicks.

## Features
- Real-time iris center detection using MediaPipe Face Mesh (refined landmarks).
- Cursor movement mapped from webcam frame to full screen with smoothing.
- Blink/wink detection for left/right clicks with cooldowns to prevent accidental repeated clicks.
- On-screen debugging overlay (landmarks, iris centers, EAR values).
- Toggle tracking on/off with `Space` and quit with `q`.

## Requirements
- Python 3.8+
- Webcam

## Install
```bash
# create venv (optional)
python -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate      # Windows

pip install opencv-python mediapipe pyautogui numpy
