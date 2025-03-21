# CSCI611 - Assignment 3: Small Object Detection Using YOLOv8

## 📌 Objective
This project aims to detect **small objects**—specifically **traffic signs and lights**—using the **YOLOv8** object detection model. These objects, often small and distant in vehicle-mounted camera views, require special care during model training, such as higher resolution inputs and data augmentation strategies.

---

## 📂 Dataset
- **Source**: Roboflow – [Self-Driving Cars Dataset](https://universe.roboflow.com/selfdriving-car-qtywx/self-driving-cars-lfjou)
- **Classes**: 15
  - Green Light, Red Light, Stop
  - Speed Limit signs: 10 to 120
- **Format**: YOLOv8
- **Dependencies**:
  - install ultralytics roboflow opencv-python torch torchvision torchaudio
