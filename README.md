# ☀️ AI-Powered Solar Panel Defect Detection System

This project uses Computer Vision and Deep Learning techniques to detect solar panel defects such as cracks, dust accumulation, and damaged cells using YOLOv8 and OpenCV.

---

# 📌 Project Overview

Solar panels often develop defects that reduce energy efficiency and require manual inspection.  
This project automates fault detection using AI-powered image processing and object detection techniques.

The system analyzes solar panel images and identifies faulty regions in real time.

---

# 🧠 Objective

To build a Computer Vision-based system that detects and classifies solar panel defects for automated monitoring and predictive maintenance.

---

# 🧩 Features

- Crack Detection
- Dust Accumulation Detection
- Damaged Cell Identification
- Real-Time Object Detection
- Bounding Box Visualization
- Confidence Score Prediction
- Streamlit Interactive Dashboard

---

# ⚙️ Technologies Used

- Python 🐍
- OpenCV
- YOLOv8
- Streamlit
- NumPy
- Pandas
- Matplotlib

---

# 🧮 Steps Performed

## Data Collection
- Collected solar panel defect image datasets.
- Organized images into multiple defect categories.

## Image Processing
- Applied preprocessing and image enhancement techniques.
- Resized and normalized images for model training.

## Model Building
- Implemented YOLOv8 object detection model for defect detection.
- Trained the model to identify damaged regions in solar panels.

## Defect Detection
- Predicted defects with bounding-box visualization and confidence scores.
- Classified defects such as cracks, dust accumulation, and damaged cells.

## Deployment
- Built a Streamlit-based web application for real-time solar panel defect analysis.

---

# 📊 Results

| Metric | Performance |
|---|---|
| Detection Accuracy | ~92% |
| Real-Time Prediction | Successful |
| Defect Classification | High Accuracy |

---

# 🚀 How to Run

Clone this repository:

```bash
git clone https://github.com/yourusername/AI-Solar-Panel-Defect-Detection.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```


