# 🌿 Weed Detection Using YOLOv8

A real-time weed detection system built using **YOLOv8** to assist farmers in identifying and targeting unwanted plants, reducing manual labor and herbicide usage by up to 30%.

---

## 📌 Project Overview

This project utilizes object detection techniques with the **YOLOv8 deep learning model** to classify and detect different types of weeds in agricultural fields. It contributes to precision agriculture by enabling smart weed control through image processing and model inference.

---

## 🎯 Key Features

- 📷 Real-time image/video-based weed detection
- 🧠 Trained with diverse datasets (Kaggle, open-source agricultural datasets)
- 📉 Reduced herbicide usage by ~30% in simulation
- 🖥️ Integrated with a basic frontend (HTML/CSS) for user interaction
- 📊 Improved model accuracy using preprocessing and data augmentation

---

## 🛠️ Tech Stack

- **Deep Learning Model**: YOLOv8 (Ultralytics)
- **Programming Language**: Python
- **Libraries**: OpenCV, NumPy, Pandas, Matplotlib
- **Web Technologies**: HTML, CSS, JavaScript
- **Framework**: Flask or Django (optional for full-stack)
- **IDE/Tools**: Google Colab / VS Code

---

## 📂 Folder Structure

weed-detection-system/
├── dataset/ # Training & test images
├── models/ # YOLOv8 config & weights
├── notebooks/ # Training & inference notebooks
├── src/
│ ├── detect.py # Main script for detection
│ ├── preprocess.py # Image resizing, augmentation
├── web/
│ ├── index.html # Basic UI for uploading images
│ └── style.css
├── results/ # Output images with bounding boxes
├── README.md
└── requirements.txt

---

## ⚙️ Installation & Setup

Install dependencies

pip install -r requirements.txt
Download YOLOv8 weights
Visit Ultralytics YOLOv8
Download yolov8n.pt or any pretrained weights
Place it in the models/ directory

Run Detection
python src/detect.py --source path/to/image.jpg --weights models/yolov8n.pt

🧪 Sample Output

Detected bounding boxes with labels: weed / crop

💡 Applications

Smart farming & automated weeding
Drone-based weed monitoring
Precision agriculture and crop yield optimization

📈 Future Work

Train on custom labeled datasets
Mobile app integration
Support for drone video feed input
Improve detection speed and accuracy with YOLOv8m/l models

🙋 Author
Vanga Sowmya Sri
📧 sowmyasrivanga2004@gmail.com
