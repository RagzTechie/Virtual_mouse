# 🖱️ Virtual Mouse Controller using Hand Gestures 🤖✋

This project enables real-time control of your computer mouse using hand gestures detected via webcam, powered by Python, OpenCV, and MediaPipe.

---

## 📌 Features

- 🖐️ **Hand Landmark Detection** using MediaPipe
- 🖱️ **Cursor Movement** by touching thumb to index base
- 👆 **Left Click** 
- 👉 **Right Click** 
- ✌️ **Double Click**
- 📸 **Screenshot Capture** with a specific gesture (saved to `D:\screenshot`)
- 🪞 Real-time webcam feed with hand landmarks and live control

---

## 🛠️ Technologies Used

- Python
- OpenCV
- MediaPipe
- NumPy
- PyAutoGUI

---

## 🖥️ How it Works

Each gesture is detected based on angles between hand landmarks and distances between fingers.

| Gesture | Action |
|--------|--------|
| **Thumb touches index base** | Start cursor control |
| **Thumb + Index erect; others bent** | Scroll (based on index movement) |
| **Thumb & Middle erect; Index fold** | Left click |
| **Thumb + Index erect;Middle finger fold** | Right click |
| **Both index and middle bent** | Double click |
| **Fingers bent + thumb near index** | Take screenshot |

---

