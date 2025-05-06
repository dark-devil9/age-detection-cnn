# 🧠 Age Detection Using Deep Learning

This project predicts a person’s age based on their facial image using a Convolutional Neural Network (CNN). It includes training the model on the UTKFace dataset and deploying it in a real-time webcam-based application.

## 📌 Features

- Predicts age from facial images using CNN
- Trained on the UTKFace dataset (20K+ images)
- Real-time age detection via webcam using OpenCV
- Age range classification for clearer output (e.g., "10–20", "28–45")

---

## 🖼 Dataset

- **Name:** [UTKFace Dataset](https://susanqq.github.io/UTKFace/)
- **Size:** ~20,000 facial images
- **Labels:** Age (0–116), Gender, Ethnicity (only Age used here)
- **Format:** `age_gender_ethnicity_date.jpg` (age is extracted from the filename)

---

## 🧪 Model Architecture

The model is a CNN built with TensorFlow/Keras:

