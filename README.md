
#  Visually Impaired Assistant (AI-Powered Real-Time Vision System)

This project is an AI-powered assistive tool for the **visually impaired**, using a smartphone/IP webcam to analyze surroundings in real-time.

 **Features**:
-  **Object Detection** using YOLOv8
-  **Text Recognition** from detected regions using Tesseract OCR
-  **Emotion Detection** of people in view using DeepFace
-  Live video stream via IP webcam
-  Modular, easy to extend

---

## 🔧 How It Works

- Press **`o`** → Detect objects and highlight bounding boxes
- Press **`t`** → Extract text from objects like signs/books
- Press **`e`** → Analyze emotions on faces in the frame
- Press **`q`** → Quit the application

---

## 🛠️ Tech Stack

- `Python`
- `OpenCV` for image processing and camera feed
- `YOLOv8` via `ultralytics` for object detection
- `pytesseract` for OCR
- `DeepFace` for emotion detection

---

## 🚀 Installation & Setup

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/visually-impaired-assistant.git
cd visually-impaired-assistant
