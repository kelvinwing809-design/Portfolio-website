# 🃏 Playing Card Classification

A Computer Vision and Deep Learning project that utilizes a Convolutional Neural Network (CNN) to classify 53 distinct playing card categories (52 standard cards + 1 Joker card). Built using Python, TensorFlow, Keras, and OpenCV.

---

## 📖 Project Overview

Image classification in varying lighting, rotation, and background conditions can be challenging for standard algorithms. This project leverages Deep Convolutional Neural Networks (CNNs) to perform accurate card recognition from images, handling visual pre-processing with OpenCV and classification through TensorFlow/Keras.

---

## 🛠️ Tech Stack & Dependencies

* **Language:** Python 3.x
* **Deep Learning:** TensorFlow, Keras
* **Computer Vision:** OpenCV
* **Data Processing & Visualization:** NumPy, Pandas, Matplotlib

---

## ✨ Key Features

* **53-Class Classification:** Recognizes standard 52 playing cards plus the Joker.
* **Image Preprocessing Pipeline:** Uses OpenCV for image resizing, normalization, and color space adjustments.
* **Data Augmentation:** Applies rotation, zoom, and shifts to improve model generalization and combat overfitting.
* **Model Evaluation:** Detailed accuracy/loss graphs and confusion matrix visualization.

---

## 📂 Project Structure

```text
.
├── dataset/
│   ├── train/          # Training images categorized by card
│   ├── test/           # Test set for final evaluation
│   └── valid/          # Validation set during training
├── notebooks/          # Jupyter Notebooks for experimentation
├── train.py            # Main training script
├── predict.py          # Inference script for single image prediction
├── requirements.txt    # Python dependencies
└── README.md
