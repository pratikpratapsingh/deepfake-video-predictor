# 🎭 Deepfake Video Detection System

## 📌 Overview
This project is an AI-powered web application that detects whether a video is REAL or FAKE using deep learning.

It uses a fine-tuned **Xception model** to analyze video frames and classify them based on manipulation artifacts.

---

## 🚀 Features
- Upload video (MP4)
- Frame extraction using OpenCV
- Deep learning prediction using Xception
- REAL / FAKE classification
- Simple web interface

---

## 🧠 Tech Stack
- Python
- FastAPI
- TensorFlow / Keras
- OpenCV
- HTML, CSS, JavaScript

---

## ⚙️ How It Works
1. User uploads video
2. Frames are extracted
3. Each frame is processed
4. Model predicts REAL / FAKE
5. Final result based on average score

---

## 📊 Results

### Fake Video
![Fake Output](screenshots/fake_output.png)

### Real Video
![Real Output](screenshots/real_output.png)

---

## 🏗️ Setup Instructions

### 1. Clone repo
```bash
git clone https://github.com/your-username/deepfake-video-detection.git
cd deepfake-video-detection
