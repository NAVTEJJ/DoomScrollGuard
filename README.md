# 🛑 DoomScrollGuard

An AI-powered real-time gaze tracking system that detects potential *doomscrolling behavior* using computer vision and triggers an intervention alert.

Built using:
- Python
- OpenCV
- MediaPipe FaceMesh

---

## 🚀 Problem Statement

Doomscrolling (excessive downward phone scrolling) reduces productivity and increases digital fatigue.

DoomScrollGuard detects sustained downward gaze using real-time eye landmark tracking and triggers an intervention video to break the habit loop.

---

## 🧠 How It Works

1. Captures webcam feed using OpenCV
2. Uses MediaPipe FaceMesh to extract facial landmarks
3. Calculates iris-to-eyelid ratio
4. Detects sustained downward gaze
5. After a configurable time threshold:
   - Plays an intervention video
   - Displays warning overlay

---

## 🎯 Features

- Real-time eye tracking
- Downward gaze detection
- Timer-based debounce logic
- Automatic intervention trigger
- Warning overlay UI
- Lightweight & fast

---

## 🛠 Tech Stack

- Python 3.9+
- OpenCV
- MediaPipe
- NumPy


