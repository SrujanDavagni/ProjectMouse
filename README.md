#  Hand Gesture Controlled Mouse (Jupyter Notebook)

Control your mouse with hand gestures using your webcam!  
This project uses **OpenCV**, **MediaPipe**, and **PyAutoGUI** to detect hand landmarks in real-time and control the mouse cursor using gestures — all from a **Jupyter Notebook**.

---

##  Project Structure

E:\ProjectMouse
├── HandGestures.ipynb # Main notebook for gesture control
├── README.md # Project documentation


---

##  Features

-  Real-time hand tracking with MediaPipe.
-  Mouse movement using index + middle fingers.
-  Mouse click triggered by pinching index + thumb.
-  Smooth cursor motion using interpolation.
-  FPS display on camera window for performance monitoring.

---

##  Technologies Used

- **Python 3.x**
- [OpenCV](https://opencv.org/)
- [MediaPipe](https://mediapipe.dev/)
- [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/)
- Math & Time (built-in)

---

##  Installation

Install the required packages using pip:

```bash
pip install opencv-python mediapipe pyautogui

Or inside the Jupyter Notebook:

!pip install opencv-python mediapipe pyautogui

##  Running

1.Launch Jupyter Notebook:
  cd E:\ProjectMouse(Your Specific folder)
  jupyter notebook
2.Open HandGestures.ipynb.
3.Run each cell step by step.
4.Make sure your webcam is accessible, and Python has screen control access.