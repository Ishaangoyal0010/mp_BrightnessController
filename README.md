# Gesture Controlled Brightness & Volume using OpenCV + MediaPipe

This is a fun project I built that lets me control my laptop’s **brightness** and **volume** using just my hand gestures, without touching the keyboard. I used **OpenCV** for video processing and **MediaPipe** to track hand landmarks in real time.

## The Idea Behind This
I wanted to explore real-time hand tracking and do something interactive with it. So I thought:
"Why not control basic system features like brightness and volume using finger gestures?"

## 🎯 What It Does
Raise thumb and index finger (Left hand) → Adjust screen brightness
Raise thumb and index finger (Right hand) → Adjust system volume
Real-time feedback using green lines between fingertips
Completely touchless and intuitive interface

## 💻 Tech Stack

- Python
- OpenCV
- MediaPipe (for hand tracking)
- pycaw (for system volume control)
- screen-brightness-control (for brightness control)

## Why I Built This
As someone exploring computer vision and human-computer interaction, this was a hands-on way to learn:
- Real-time landmark tracking
- Hardware control via software
- Simple logic to gesture mapping
- It might look simple, but it taught me a lot about working with live camera feeds, system APIs, and how to translate physical motion into digital actions.

## ⚙️ How to Run
- pip install numpy opencv-python mediapipe pycaw screen-brightness-control
- Clone the repo
```bash
git clone https://github.com/your-username/gesture-control
cd gesture-control

