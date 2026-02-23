# 🎮 HILL CLIMB RACING – GESTURE CONTROLLED USING COMPUTER VISION

This project implements **real-time gesture-based control** for Hill Climb Racing using Computer Vision techniques.

Instead of using keyboard input, the game is controlled through **hand gestures detected via webcam**.

The system captures live video using **OpenCV** and detects hand landmarks using **MediaPipe**.

Based on predefined finger positions and landmark coordinate comparisons, gestures are mapped to game actions:

✋ **Gesture 1 → ACCELERATE**
✋ **Gesture 2 → BRAKE**

The gesture recognition is implemented using **rule-based coordinate logic**.

---

# 🛠 TECH STACK (Library used)

* PYTHON
* OPENCV (CV2)
* MEDIAPIPE
* NUMPY
* TIME

---

# ⚙️ HOW IT WORKS

1️⃣ Webcam captures real-time video frames.

2️⃣ Each frame is processed using OpenCV.

3️⃣ MediaPipe detects **21 hand landmarks**.

4️⃣ Landmark coordinates are extracted.

5️⃣ Gesture logic is applied using relative coordinate comparison.

6️⃣ Corresponding key action is triggered in the game.

The system runs in **real time with minimal latency**.

---

# 🧠 CORE CONCEPTS USED

* REAL-TIME IMAGE PROCESSING
* HAND LANDMARK DETECTION
* COORDINATE GEOMETRY USING NUMPY
* RULE-BASED GESTURE RECOGNITION
* HUMAN-COMPUTER INTERACTION (HCI)

---

# 🚀 INSTALLATION

```
git clone https://github.com/jiyajahnavi/hill-climb-gesture-control.git
cd hill-climb-gesture-control
pip install -r requirements.txt
python main.py
```

---
