# VisionX: Real-Time Object Detection using YOLOv8

VisionX is a powerful real-time object detection system built with **YOLOv8**, **OpenCV**, and **Flask**. Designed as a Final Year Project (FYP), it showcases how cutting-edge AI models can be deployed to perform object recognition live from a webcam stream with high accuracy and speed.

---

## 🚀 Features

* 🎯 Real-time object detection with YOLOv8
* 🎥 Live webcam stream displayed on a web interface
* 🧠 Powered by ultralytics' state-of-the-art YOLOv8 models
* ✅ Easy-to-run Flask backend
* 💻 Lightweight and runs on standard laptops

---

## 📁 Project Structure

```
live_object_detection/
├── main.py                  # Flask app with YOLOv8 + OpenCV
├── models/
│   └── yolov8n.pt          # Pretrained model file
├── templates/
│   └── index.html          # Frontend HTML UI
├── static/
│   └── style.css           # CSS for frontend design
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

---

## ⚙️ Requirements

* Python 3.8 – 3.11

### Install Dependencies

```bash
pip install -r requirements.txt
```

### requirements.txt

```
ultralytics
opencv-python
flask
```

---

## 🔧 How to Run

1. Clone the repo

```bash
git clone https://github.com/your-username/visionx-detection.git
cd visionx-detection
```

2. Activate virtual environment (optional but recommended)

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

3. Download YOLOv8 model
   Manually place `yolov8n.pt` in the `models/` folder from:
   [https://github.com/ultralytics/assets/releases/download/v0.0.0/yolov8n.pt](https://github.com/ultralytics/assets/releases/download/v0.0.0/yolov8n.pt)

4. Run the Flask app

```bash
python main.py
```

5. Open your browser:

```
http://127.0.0.1:5000

## 🎓 Author & Credits

**Name**: Abdullah Attique
**Project**: Live Object Detection

Special thanks to:

* [Ultralytics](https://github.com/ultralytics) for YOLOv8
* [OpenCV](https://opencv.org/) for vision tools

---

## 📌 Future Enhancements

* 🎤 Voice command integration
* 🧠 Custom training for specific object classes (e.g. tennis ball)
* 💾 Detection log saving and analysis
* 🖼️ Screenshot capture feature