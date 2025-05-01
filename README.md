# 🚗 Traffic Vehicle Detection & Speed Estimation with YOLOv12n and Faster R-CNN

This project is a full-stack Flask + Gradio web application for detecting, tracking, counting, and estimating the speed of vehicles (cars, motorcycles, trucks) in traffic videos using **YOLOv12n** and **Faster R-CNN** models.


## 🔴 Live Demo

🛰 **Deployed on Hugging Face Spaces**:  
👉 [Traffic Vehicle Count & Speed Detection](https://huggingface.co/spaces/maliahson/Traffic_vehicles_count_using_yolo12n_Faster-RCNN)

---

## 📌 Features

- 🚦 Detect vehicles in video using **YOLOv12n** or **Faster R-CNN**
- 📉 Estimate vehicle **speed in km/h**
- 🧮 Vehicle type counting (car, motorcycle, truck)
- 🛣️ Draw counting lines
- ✅ Custom trained model support
- 🎞️ Video processing with visual overlays

---

## 🧠 Models Used

| Model       | Purpose                | Source              |
|-------------|------------------------|---------------------|
| YOLOv12n    | Real-time object detection | `ultralytics`       |
| Faster R-CNN | High-accuracy vehicle detection | Custom-trained PyTorch model |

> ⚠️ You must provide `yolo12n.pt` and `fasterrcnn_vehicle_detector.pth` in the project root.

---

## 🧰 Dependencies

Install the following Python packages:

```bash
pip install -r requirements.txt
