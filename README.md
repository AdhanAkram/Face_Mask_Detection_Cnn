# Real-Time Face Mask Detection Using Machine Learning

## Overview
This project implements a **real-time face mask detection system** using **deep learning**. It can classify whether a person is wearing a mask or not through live camera feed or uploaded images. The model leverages **MobileNetV2** as the base and adds custom layers for binary classification.

---

## Features
- Detects faces in real-time using a webcam or uploaded images.
- Classifies faces as **Mask** or **No Mask**.
- Provides a simple interface to test images.
- Trained on a curated dataset of masked and unmasked faces.

---

## Dataset
The dataset used contains two classes:
1. `with_mask` – Images of people wearing masks.
2. `without_mask` – Images of people not wearing masks.  

The dataset is organized in the standard **train-validation split** using `ImageDataGenerator`.

---

## Requirements
- Python 3.8+
- TensorFlow 2.x
- Keras
- OpenCV
- NumPy
- Pillow
- Matplotlib
- Google Colab (optional)

Install dependencies:
```bash
pip install tensorflow keras opencv-python numpy pillow matplotlib

