# Handwritten Digit Recognizer (MNIST)

## 📌 Project Overview
This project is a simple deep learning model that recognizes handwritten digits (0–9) using the MNIST dataset.

It uses a Neural Network built with TensorFlow and Keras to classify grayscale images of digits.

---

## 🚀 Features
- Uses MNIST dataset (70,000 images)
- Neural network model using Keras
- Achieves high accuracy on test data
- Predicts handwritten digits from input images
- Visualization using Matplotlib

---

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

---

## 📊 Dataset
The MNIST dataset contains:
- 60,000 training images
- 10,000 testing images
- Each image is 28x28 pixels (grayscale)

---

## ⚙️ How It Works
1. Load MNIST dataset
2. Normalize pixel values (0–255 → 0–1)
3. Build neural network:
   - Flatten layer
   - Dense layer (ReLU)
   - Output layer (Softmax)
4. Train model
5. Evaluate accuracy
6. Predict new digits

---

## ▶️ How to Run

### Option 1: Google Colab
1. Open the notebook in Google Colab
2. Run all cells

### Option 2: Local Machine
```bash
pip install tensorflow matplotlib numpy
