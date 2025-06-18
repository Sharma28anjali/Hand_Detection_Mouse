# 🖐️ Hand Detection Mouse

A virtual mouse system powered by hand gestures using **Python**, **MediaPipe**, and **OpenCV**. This project lets you control your mouse pointer with just your hand — no physical mouse needed!

## 📌 Features

- **Cursor Movement**: Move your index finger to move the mouse pointer on screen.
- **Left Click**: Bring your thumb close to the index finger.
- **Right Click**: Bring your ring finger close to the index finger.
- **Scroll Up**: Raise your middle finger above the index finger.

## 📽️ Demo

> ✋ Point, click, and scroll — all without touching your mouse!

![image](https://github.com/user-attachments/assets/435b6ba9-2ef3-4d97-8452-fba8b6715b62)


## 🛠️ Technologies Used

- **Python**
- **OpenCV** - For capturing and processing webcam input
- **MediaPipe** - For real-time hand tracking
- **NumPy** - For distance calculations between landmarks
- **PyAutoGUI** - For controlling the mouse on screen


### Step-by-Step

1. Clone this repository:
```bash
git clone https://github.com/yourusername/hand-detection-mouse.git
cd hand-detection-mouse
pip install opencv-python mediapipe pyautogui numpy
python hand_mouse.py
hand-detection-mouse/
├── hand_mouse.py        # Main application script
└── README.md            # Project documentation




