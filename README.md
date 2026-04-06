# 🚨 Smart Motion Alarm System

A real-time motion detection and alarm system built using Python and OpenCV. This project detects movement through a camera feed and triggers an alert when motion is detected. It can be used for basic security and surveillance purposes.

---

## 📌 Features

- 🎥 Real-time video capture using webcam
- 🧠 Motion detection using frame differencing
- 🚨 Alarm/alert trigger on motion detection
- ⚡ Lightweight and efficient processing
- 🛠️ Easy to customize and extend

---

## 🛠️ Technologies Used

- Python
- OpenCV (cv2)

---

## ⚙️ How It Works

1. Capture live video feed from the webcam.
2. Convert frames to grayscale for processing.
3. Apply Gaussian blur to reduce noise.
4. Compare consecutive frames to detect motion.
5. If motion exceeds a threshold:
   - Trigger an alert (sound/print message)
   - Highlight motion area

---
