🖱️ Virtual Mouse using Python
📌 Overview

The Virtual Mouse is a computer vision project that allows users to control the mouse pointer using hand gestures instead of a physical mouse. Using OpenCV, Mediapipe, and PyAutoGUI, it detects hand landmarks via webcam and maps gestures to mouse actions like moving the cursor, clicking, dragging, and scrolling.

This project demonstrates how AI-powered gesture recognition can create touch-free, intuitive, and futuristic human-computer interaction.

🚀 Features

✅ Cursor movement using index finger

✅ Left click (thumb + index finger gesture)

✅ Right click (thumb + middle finger gesture)

✅ Drag & Drop (thumb + ring finger gesture)

✅ Scrolling (thumbs up/down gestures)

✅ On-screen gesture instructions for user guidance

✅ Works in real time with any standard webcam

🛠️ Tech Stack

Python 3.x

OpenCV – real-time video processing

Mediapipe – hand and finger landmark detection

PyAutoGUI – for controlling mouse actions

📂 Project Structure
📦 Virtual-Mouse
 ┣ 📜 virtual_mouse.py      # Main Python script
 ┣ 📜 requirements.txt      # Dependencies
 ┣ 📜 README.md             # Project documentation
 ┗ 📂 screenshots/          # (Optional) Demo images or GIFs

⚡ Installation & Usage

Install dependencies:

pip install -r requirements.txt


Run the program:

python virtual_mouse.py


Control your computer with hand gestures 🎉

🎮 Controls / Gestures

🖱️ Move Cursor → Move your Index Finger

👆 Left Click → Bring Thumb close to Index Finger

👉 Right Click → Bring Thumb close to Middle Finger

✊ Drag & Drop → Hold Thumb close to Ring Finger

👍 Scroll Up/Down → Thumbs Up (scroll up), Thumbs Down (scroll down)

📌 Future Improvements

Gesture customization support

Multi-hand detection

Enhanced accuracy in low-light environments

Hybrid control with voice commands
# Virtual-Mouse
