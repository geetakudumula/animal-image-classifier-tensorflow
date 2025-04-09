# 🧠 Animal Image Classifier using TensorFlow (Cats, Dogs & Raccoons)

This is a small, practical project I built to get hands-on with TensorFlow and Keras. The goal was to create a simple neural network that can classify grayscale images into three categories: **cat**, **dog**, or **raccoon**.

For this first version (V1), I generated synthetic grayscale image data (28x28 pixels) just to keep things simple and focus on getting the core model architecture and training workflow right.

---

## 🚀 What This Project Covers

- Building a neural network model from scratch with Keras
- Using synthetic image data for quick experimentation
- One-hot encoding for multi-class classification
- Model training and evaluation
- Making predictions and printing confidence scores
- Jupyter Notebook for step-by-step walkthrough

---

## 🧰 Tools & Frameworks Used

- Python 3.8+
- TensorFlow / Keras
- NumPy
- Jupyter Notebook

---

## 🧠 Model Overview

```text
Input: 28x28 grayscale image  
Layers:
- Flatten
- Dense (128 units, ReLU)
- Dense (64 units, ReLU)
- Output Dense (3 units, Softmax)
