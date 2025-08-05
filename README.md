# Final-year-project

# 👁️🖱️ Virtual Cursor Control Using Eye Tracking and Hand Gestures

This project aims to create a virtual mouse system that allows users to control the computer cursor using their **eye movements** and **hand gestures**. It provides a **touchless**, **intuitive**, and **accessible** way of interacting with the computer, especially useful for differently-abled users and in hands-free environments like surgeries, clean rooms, etc.

---

## 📌 Features

- 👁️ Eye tracking-based cursor control
- ✋ Hand gesture-based click simulation
- 🧠 Real-time detection using computer vision
- 💻 Uses webcam as the only input device
- 🧩 Easy-to-use, lightweight, and customizable

---

## 🛠️ Technologies Used

- `Python 3.x`
- `OpenCV` – For image processing and webcam capture
- `MediaPipe` – For real-time hand and face landmark detection
- `PyAutoGUI` – For controlling mouse movements and clicks
- `NumPy` – For matrix and numerical operations

---

## 🧪 How It Works

1. **Webcam** captures real-time video feed.
2. **MediaPipe** detects hand landmarks (for gestures) and face landmarks (for eyes).
3. **Eye movement** is used to move the cursor.
4. **Finger gestures** (like index and thumb pinch) are used to click or perform actions.
5. **PyAutoGUI** maps these gestures to actual mouse movements/clicks.

---

