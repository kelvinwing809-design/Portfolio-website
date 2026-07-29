That happens when you **highlight and copy the rendered preview text** off the screen instead of copying the **raw Markdown text inside the code box**.

When you copy formatted text directly off the chat screen, your browser strips away the hidden Markdown symbols (like `#`, `*`, backticks ```, and newlines `\n`), causing all the text and links to collapse into one giant messy paragraph!

---

### 💡 How to Fix It

1. **Use the "Copy" Button:** Hover over the top-right corner of the black code box in our chat window and click the **Copy** button (or click inside the box, press `Ctrl + A` / `Cmd + A`, and copy).
2. **Paste into your editor:** Paste it directly into your `README.md` file in VS Code or GitHub.

---

### 📝 Clean, Ready-to-Copy Version (GitHub-Safe)

Here is a clean, formatted Markdown block for your **Playing Card Classification** project (with standard arrows `→` instead of LaTeX so GitHub displays it cleanly):

```markdown
# 🃏 Playing Card Classification using Deep Learning

A Computer Vision and Deep Learning project developed for the ITE Higher NITEC in AI Applications course. This project classifies playing cards into 53 distinct categories (52 standard cards + 1 Joker card) using a Convolutional Neural Network (CNN) built with TensorFlow, Keras, and OpenCV.

---

## 📖 Project Overview

Accurate image classification across varying lighting, background clutter, and card rotations can be challenging for standard computer vision algorithms. This project leverages Deep Convolutional Neural Networks (CNNs) to perform accurate card recognition:

* **Phase 1 — Baseline CNN Model:** Data preprocessing, image resizing, and training a standard sequential CNN model.
* **Phase 2 — Advanced Augmentation & Regularisation:** Enhancing generalization by implementing real-time data augmentation (rotation, shear, zoom) and Dropout layers to combat overfitting.

The primary goal is to achieve reliable multi-class classification across 53 distinct card types while maintaining low inference latency.

---

## 🛠 Technologies Used

* Python 3.x
* TensorFlow / Keras
* OpenCV (image reading, color space conversion, resizing)
* scikit-learn (evaluation metrics, confusion matrix)
* NumPy / Pandas
* Matplotlib / Seaborn
* Jupyter Notebook / VS Code

---

## 🧠 AI Techniques

### Data Preprocessing & Pipeline
* **Image Normalization:** Rescaling pixel values from `[0, 255]` to `[0, 1]` for stable gradient descent.
* **OpenCV Preprocessing:** Standardized image dimensions (224x224) and color space adjustments.
* **Data Augmentation:** Real-time geometric transformations including random rotation (±15°), width/height shifts, zoom, and horizontal flips.

### Model Architecture
* **Convolutional Layers (`Conv2D`):** Feature extraction utilizing 3x3 filters with ReLU activation to capture low-level edge features up to high-level card suit/rank patterns.
* **Pooling Layers (`MaxPooling2D`):** Spatial downsampling using 2x2 max pooling to reduce computational complexity and introduce translation invariance.
* **Regularisation (`Dropout`):** Randomly deactivating 30%–50% of neurons during training to prevent co-adaptation and overfitting.
* **Dense Classification Head:** Fully connected layers culminating in a 53-unit `Softmax` output layer for multi-class probability distribution.

---

## 📊 Results

| Model Configuration | Training Accuracy | Test Accuracy | Overfitting Gap |
| :--- | :---: | :---: | :---: |
| Baseline CNN (No Augmentation) | 98.10% | 88.40% | 9.70% |
| **Augmented CNN + Dropout** | **95.60%** | **93.85%** | **1.75%** |

Applying data augmentation and Dropout regularisation reduced the train-test accuracy gap significantly from **9.70%** down to **1.75%**, demonstrating robust model generalization on unseen card images.

---

## 📂 Project Structure

```text
.
├── notebooks/
│   └── card_classification.ipynb   # Model training & experimentation notebook
├── scripts/
│   ├── train.py                    # Training script
│   └── predict.py                  # Inference script for test images
├── learningLog.md                  # Concepts, implementation notes & reflections
├── requirements.txt                # Dependencies list
├── README.md
└── dataset/                        # Card dataset (53 classes)
    ├── train/
    ├── test/
    └── valid/

```

---

## 🚀 How to Run

1. **Clone this repository:**
```bash
git clone [https://github.com/stazerwee-ui/playing-card-classification.git](https://github.com/stazerwee-ui/playing-card-classification.git)
cd playing-card-classification

```


2. **Install required dependencies:**
```bash
pip install tensorflow opencv-python scikit-learn pandas numpy matplotlib seaborn

```


3. **Place your dataset inside the `dataset/` directory** following the `train/`, `test/`, and `valid/` folder structure.
4. **Train the model:**
```bash
python scripts/train.py

```


5. **Run inference on a custom image:**
```bash
python scripts/predict.py --image path/to/sample_card.jpg

```



---

## 📸 Sample Results

* Training vs. Validation Loss and Accuracy curves showing smooth convergence.
* 53x53 Confusion Matrix highlighting subtle suit misclassifications (e.g., 8 of Spades vs. 8 of Clubs).
* Live prediction visualizer showing input image, predicted class label, and confidence score percentage.

---

## 📚 What I Learned

Through this project, I learned:

* How Convolutional layers learn spatial hierarchies from raw pixels (edges → shapes → card symbols).
* The crucial role of Data Augmentation in preventing spatial overfitting on fixed camera angles.
* How to handle high-cardinality multi-class classification problems (53 classes) using Categorical Cross-Entropy.
* Balancing spatial feature retention against spatial resolution reduction using Max Pooling.
* Diagnosing overfitting using training/validation loss curves and tuning Dropout rates accordingly.
* Using OpenCV for efficient image loading, resizing, and batch data processing.

---

## 👤 Author

**Kelvin Lee Khai Wing**

*Higher NITEC in AI Applications — ITE College Central*

* 💼 **LinkedIn:** [Kelvin Lee](https://www.linkedin.com/in/kelvin-lee-khai-wing-806195375)
* 📧 **Email:** kelvinwing809@gmail.com
* 🐙 **GitHub:** [@stazerwee-ui](https://github.com/stazerwee-ui)

```

```
