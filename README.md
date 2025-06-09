# Reidentification-in-Single-Feed
# 🧍‍♂️ Player Re-Identification Using YOLOv11 and DeepSort

## 📌 Overview

This project implements real-time player detection, tracking, and re-identification in a 15-second football video using:

- **YOLOv11** – for fast and accurate object detection (fine-tuned on player class)
- **DeepSort** – for maintaining unique and consistent player IDs across frames

It ensures that each player retains the same ID throughout the video, even after occlusion or re-entry.

---

## 🎯 Objective

The goal is to detect and track football players with unique IDs throughout a short 15-second clip using the provided YOLOv11 model.

---
requirements.txt-
ultralytics==8.0.216
deep_sort_realtime==1.3.1
torch>=1.13.0
opencv-python
numpy

# Create and activate virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # on Linux/Mac
venv\Scripts\activate     # on Windows

# Install dependencies
pip install -r requirements.txt






