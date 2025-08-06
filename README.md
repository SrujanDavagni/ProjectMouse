<<<<<<< HEAD
# 🖱️ Hand Gesture Controlled Mouse

Control your mouse cursor and click using hand gestures captured via webcam using Python, OpenCV, MediaPipe, and PyAutoGUI.

---

## 🎯 Features

- Move cursor using index and middle fingers
- Click using index and thumb pinch gesture
- Real-time hand tracking using MediaPipe
- Smooth cursor motion to reduce jitter
- FPS (Frames Per Second) display on screen

---

## 🛠️ Tech Stack

- **Python 3**
- **OpenCV** – for image processing
- **MediaPipe** – for hand tracking and landmarks detection
- **PyAutoGUI** – for controlling the mouse

---

## 🧑‍💻 How It Works

- Uses **MediaPipe** to detect and track hand landmarks.
- Recognizes:
  - Index + middle finger up = move mouse.
  - Thumb + index pinch = click.
- Converts hand position from camera coordinates to screen resolution.
- Smoothens the cursor movement to avoid jitter.

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/SrujanDavagni/ProjectMouse.git
cd gesture-mouse

# Install dependencies
pip install opencv-python mediapipe pyautogui
=======
# ProjectMouse
>>>>>>> 6ccdb94eb81b1aaa16cbbb6f17b222403924d9a2
