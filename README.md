# Surface Defect Detection Using YOLO

An AI-powered computer vision application for detecting surface defects in **steel and wood materials** using YOLO-based object detection models. The project includes an interactive Streamlit interface that allows users to select the material, upload an image, and visualize detected defects.

## Overview

Surface defects can affect the quality, durability, and usability of manufactured materials. Manual inspection can be time-consuming and may lead to inconsistent results.

This project applies deep learning and computer vision techniques to automate the inspection process. Separate trained YOLO models are used for steel and wood defect detection, while a Streamlit application provides an easy-to-use interface for testing the models.

## Key Features

- 🔍 **Automated Defect Detection**
  - Detects surface defects using trained YOLO models.

- 🏭 **Steel & Wood Inspection**
  - Supports two material categories:
    - Steel
    - Wood

- 🤖 **YOLO Object Detection**
  - Uses trained YOLO models for accurate defect localization.

- 🖼️ **Image-Based Inspection**
  - Upload an image and receive visual detection results.

- 📊 **Detection Visualization**
  - Displays bounding boxes and detected defect classes directly on the image.

- 🖥️ **Interactive Streamlit Interface**
  - Simple interface for selecting the material, uploading images, and viewing results.

## Technologies Used

- **Python**
- **YOLO**
- **OpenCV**
- **Streamlit**
- **NumPy**
- **Deep Learning**
- **Computer Vision**

## Project Structure

```text
Surface-Defect-Detection/
│
├── models/
│   ├── metal.pt
│   └── wood.pt
│
├── app.py
├── requirements.txt
└── README.md
