# 👕 TryOnX – AI Virtual Shirt Try-On System

> A gesture-controlled virtual try-on system built with Python, OpenCV, and MediaPipe, allowing users to visualize shirts on their body using real-time pose detection and hand gestures.


## 🧠 Overview

**TryOnX** is a computer vision-powered application that overlays shirts onto a user's body using a webcam. By tracking body landmarks and hand gestures, users can swipe through different shirt options simply by raising their hands—no need for keyboard input!

This project demonstrates the creative integration of:

- 📸 Real-time pose tracking with **MediaPipe**
- 🧠 Landmark detection with **cvzone**
- 🔁 Interactive hand gesture navigation
- 🧥 Shirt overlay with position/scale adjustment using math + OpenCV


## 🚀 How It Works

- Uses your **webcam** to detect your upper body with **MediaPipe Pose**
- Tracks landmark 11 (left shoulder) and 12 (right shoulder)
- Resizes & positions transparent shirt images to match your shoulder width
- Uses **hand raise detection** (landmarks 15 & 16) to navigate between shirts
- Buttons on screen provide feedback for user actions


## 🛠 Technologies Used

| Tool        | Purpose                          |
|-------------|----------------------------------|
| 🐍 Python   | Core programming language        |
| 📸 OpenCV   | Image capture, manipulation      |
| 🌀 cvzone   | Simplified overlay + detection   |
| 🧍 MediaPipe Pose | Real-time pose estimation |
| 🖼 PNG Overlays | For rendering transparent shirt layers |

## ✅ Features

- 🧥 Virtual try-on with realistic shirt scaling
- ✋ No keyboard/mouse – gesture-based control
- 📐 Dynamic offset/scale for various body types
- ⚡ Lightweight & runs in real-time

## 🙋‍♂️ Author

Made with 💻 and ❤️ by **Samip Suebdi **  
• [GitHub](https://github.com/samip-subedi)



