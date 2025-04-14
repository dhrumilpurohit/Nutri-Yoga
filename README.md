# 🧘‍♂️ Nutri_yoga: AI-Based Yoga Trainer

Welcome to the **Nutri-Yoga**! This is a real-time yoga posture detection and feedback system built using **MediaPipe** and **OpenCV**. It helps users perform yoga poses correctly by analyzing their posture and providing instant visual feedback.

## 📌 Features

- ✅ Real-time pose detection using webcam
- 📍 Accurate landmark tracking with MediaPipe's pose estimation
- 📸 Visual feedback using OpenCV overlays
- 🧘‍♀️ Supports multiple yoga poses
- 🔄 Frame-by-frame analysis for improved posture correction
- 💡 Easy to use and lightweight — no model training required

## 🛠️ Tech Stack

- **Python**
- **MediaPipe**
- **OpenCV**
- **NumPy**

## 🚀 How It Works

1. Captures live video from the user's webcam.
2. Uses MediaPipe to detect 33 key body landmarks.
3. Analyzes angles between joints to determine the accuracy of the yoga pose.
4. Draws feedback (e.g., correct/incorrect pose, angles) in real-time on the video feed using OpenCV.
