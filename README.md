# 🧠 Animal Image Classifier (Cats, Dogs & Raccoons) — TensorFlow V1

This is a beginner-friendly yet structured deep learning project that classifies grayscale images of **cats**, **dogs**, and **raccoons** using a simple neural network built with **TensorFlow** and **Keras**. The model was trained on **synthetic grayscale data** and demonstrates key concepts such as:

- Confidence vector generation
- Model inference
- One-hot encoding
- Model architecture tuning
- Training vs. validation performance tracking

> ✅ This project was developed by [Geeta Kudumula](https://www.linkedin.com/in/geetakudumula) as part of a practical AI learning path and will be evolved in future versions to use real-world image datasets (e.g., CIFAR-10).

---

## 🛠️ Tools & Frameworks

- Python 3.8+
- TensorFlow / Keras
- NumPy
- Jupyter Notebook

---

## 📊 Model Architecture

```text
Input: 28x28 grayscale images  
Model:  
- Flatten  
- Dense (128, relu)  
- Dense (64, relu)  
- Output Dense (3, softmax)

📁 Files
File	Description
animal_classifier_v1.ipynb	Jupyter Notebook: model training, evaluation & predictions
README.md	Project overview and instructions
🧪 Output Sample
csharp
Copy
Edit
Test Image 1: Predicted as 'Cat' with 0.55 confidence
Test Image 2: Predicted as 'Dog' with 0.48 confidence
Test Image 3: Predicted as 'Raccoon' with 0.61 confidence
🔮 What's Next (V2)
✅ Coming Soon in V2:
We’ll use real image data (CIFAR-10) to build a stronger classifier and apply model evaluation techniques including:

Confusion matrix

Accuracy visualization

Model persistence & loading

👩‍💻 Author
Geeta Kudumula
AI & Streaming Architect | Kafka | Cloud | AI Enthusiast
📍 LinkedIn

⭐ Star This Repo
If you find this useful, feel free to ⭐ the repo and follow for future updates!

yaml
Copy
Edit

---

## ✅ 3. Copy This Into Your `README.md`

Paste it into your local `README.md`, save, then commit:

```bash
git add README.md
git commit -m "Updated README with full project details"
git push
