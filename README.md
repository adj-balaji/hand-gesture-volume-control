# 🎛️ Volume Control using Hand Tracking

## 🚀 Overview

This project allows users to control system volume using **hand gestures** captured through a webcam.

Using **Computer Vision and Hand Tracking**, the distance between the thumb and index finger dynamically adjusts the system volume in real time.

---

## 🎯 Objective

To create a **touchless and intuitive volume control system** using:

* Hand gestures
* Real-time video processing
* System-level audio control

---

## ⚙️ Features

* ✋ Real-time hand detection using MediaPipe
* 📏 Distance-based volume control
* 🎥 Live webcam interaction
* 🔊 Smooth system volume adjustment
* 🎯 Visual feedback (lines, points, volume text)

---

## 🧠 Tech Stack

* Python
* OpenCV
* MediaPipe
* NumPy
* Pycaw (Windows Audio Control)

---

## 🏗️ How It Works

1. Webcam captures live video
2. MediaPipe detects hand landmarks
3. Extract:

   * Thumb tip (Landmark 4)
   * Index finger tip (Landmark 8)
4. Calculate distance between fingers
5. Map distance → system volume
6. Update volume in real time

---

## 📊 Concept

```id="flowvc"
Hand Distance ↑ → Volume ↑  
Hand Distance ↓ → Volume ↓
```

---

## ▶️ Installation

```bash id="vc1"
git clone https://github.com/adj-balaji/hand-gesture-volume-control.git
cd hand-gesture-volume-control
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash id="vc2"
python main.py
```

---

## 📁 Project Structure

```id="vc3"
Hand-Volume-Control/
│
├── main.py
├── requirements.txt
├── README.md
```

---

## 📷 Output

* Live webcam feed
* Hand landmarks detection
* Line between fingers
* Dynamic volume display

---

## 🔧 Requirements

* Webcam
* Windows OS (for Pycaw)

---

## 📦 Dependencies

* OpenCV
* MediaPipe
* NumPy
* Pycaw

---

## 🚀 Future Improvements

* 📱 Mobile version (Android app)
* 🎮 Gesture-based media controls (play/pause/next)
* 🔊 Volume UI slider visualization
* 🧠 Multi-hand gesture recognition
* 🚗 Integration with Android Auto / Car systems

---

## 👨‍💻 Author

**BALAJI A D J**
GitHub: https://github.com/adj-balaji

---

## ⭐ If you like this project, give it a star!
