# 🚗 Road Damage Detection System

An AI-powered web application for detecting road damage from images using **YOLO object detection** and **Flask**.

Users can upload road images through the web interface, and the trained YOLO model analyzes the image and generates a detection result.

🌐 **Live Demo:** https://major-project-teod.onrender.com

---

## 📌 Overview

Road damage such as potholes, cracks, and other surface defects can affect road safety and increase vehicle maintenance costs.

This project uses a trained **YOLO object detection model** to automatically identify road damage from uploaded images.

The application combines:

- 🤖 YOLO-based object detection
- 🐍 Flask backend
- 🖼️ OpenCV and Pillow for image processing
- 🌐 HTML/CSS frontend
- ☁️ Cloud deployment using Render

---

## ✨ Features

- 📤 Upload road images
- 🤖 AI-based road damage detection
- 🔍 YOLO object detection
- 🖼️ Image processing using OpenCV
- 📊 Detection and performance visualization
- 📈 Charts dashboard
- 🔐 Login and registration pages
- 📱 Web-based interface
- ☁️ Cloud deployment
- ⚡ Production deployment using Gunicorn

---

## 🛠️ Tech Stack

### Backend

- Python
- Flask 3.1.3
- Flask-CORS 6.0.2
- Gunicorn 23.0.0

### Machine Learning

- Ultralytics YOLO 8.4.17
- PyTorch 2.10.0
- TorchVision 0.25.0

### Image Processing

- OpenCV
- Pillow
- NumPy

### Frontend

- HTML5
- CSS3
- JavaScript

### Deployment & Tools

- Git
- GitHub
- Render
- Jupyter Notebook

---

## 📂 Project Structure

Major-Project/
│
├── app.py
├── best.pt
├── data.yaml
├── requirements.txt
├── Procfile
├── 90.ipynb
├── README.md
│
├── templates/
│   ├── index.html
│   ├── home.html
│   ├── login.html
│   ├── register.html
│   ├── about.html
│   ├── charts.html
│   └── performance.html
│
└── static/
    ├── images/
    ├── results/
    ├── uploads/
    └── static.css
    
---

🤖 Machine Learning Model

The application uses a trained YOLO model provided through:

best.pt

The model is integrated with the Flask application using the Ultralytics YOLO framework.

The model processes uploaded road images and generates object detection results that are displayed through the web interface.

---
Live Application

🌐 ** https://major-project-teod.onrender.com

📊 Application Pages
Page	Purpose
🏠 Home	Main application interface
🔍 Detection	Upload and analyze road images
📊 Charts	Detection data visualization
📈 Performance	Model/application performance
ℹ️ About	Project information
🔐 Login	User login
📝 Register	User registration
🎯 Project Objectives

Automate road damage detection using computer vision
Detect road damage from images using YOLO
Provide an easy-to-use web interface
Reduce the need for manual image inspection
Integrate machine learning with a web application
Deploy an AI-powered application to the cloud
---
🔮 Future Improvements:

📍 GPS-based damage location tracking
🗺️ Road damage heatmaps
📱 Mobile application
🎥 Real-time video-based detection
📊 Advanced analytics
🔔 Automated maintenance alerts
☁️ Scalable AWS deployment
🧠 Improved model accuracy with larger datasets

---

📦 Requirements

The project uses:
Flask==3.1.3
flask-cors==6.0.2
ultralytics==8.4.17
opencv-python==4.13.0.92
numpy==2.3.2
Pillow==11.3.0
torch==2.10.0
torchvision==0.25.0
gunicorn==23.0.0
python-multipart==0.0.20

---

👨‍💻 Author
Mustafa

⭐ Support
If you find this project useful, consider giving the repository a ⭐.
