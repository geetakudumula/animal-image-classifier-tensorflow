#  Animal Image Classifier using TensorFlow (Cats, Dogs & Raccoons)

This is a small, practical project I built to get hands-on with TensorFlow and Keras. The goal was to create a simple neural network that can classify grayscale images into three categories: **cat**, **dog**, or **raccoon**.

For this first version (V1), I generated synthetic grayscale image data (28x28 pixels) just to keep things simple and focus on getting the core model architecture and training workflow right.

---

## What This Project Covers

- Building a neural network model from scratch with Keras
- Using synthetic image data for quick experimentation
- One-hot encoding for multi-class classification
- Model training and evaluation
- Making predictions and printing confidence scores
- Jupyter Notebook for step-by-step walkthrough

---

## Tools & Frameworks Used

- Python 3.8+
- TensorFlow / Keras
- NumPy
- Jupyter Notebook

---

##  Model Overview

```text
Input: 28x28 grayscale image  
Layers:
- Flatten
- Dense (128 units, ReLU)
- Dense (64 units, ReLU)
- Output Dense (3 units, Softmax)
```



## Project Files
1) animal_classifier_v1.ipynb ---> this is a	Jupyter Notebook: data simulation, training, and prediction
2) README.md	This project overview and notes


## Sample Prediction Output
Test Image 1: Predicted as 'Cat' with 0.55 confidence  
Test Image 2: Predicted as 'Dog' with 0.48 confidence  
Test Image 3: Predicted as 'Raccoon' with 0.61 confidence  

## Why I Built This
As someone working in the cloud and streaming architecture space, I wanted to extend my hands-on understanding of AI/ML workflows—especially around model training and inference. This was a quick way to brush up on TensorFlow, and now I'm planning to expand this project using real-world datasets like CIFAR-10 in the next version (V2).

## What’s Next (V2 ideas)
Use CIFAR-10 dataset instead of synthetic images

Add image visualization and training graphs

Save the trained model and load it for inference

Try deploying the model as a Flask or Streamlit app


## Author
Created by Geeta Kudumula
AIML/Cloud Solutions Architect

If You Found This Useful...
Feel free to star ⭐ this repo and follow along as I continue learning and building!

---


