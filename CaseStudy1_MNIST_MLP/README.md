# 🔢 Handwritten Digit Classification using Neural Network (From Scratch)

## 📌 Overview

This project implements a neural network from scratch (without using deep learning frameworks) to classify handwritten digits from the MNIST dataset. The model is built using NumPy and trained using forward and backward propagation.

---

## ⚙️ Technologies Used

* Python
* NumPy
* Matplotlib
* Keras (only for dataset loading)

---

## 📂 Dataset

* **MNIST Dataset**
* 70,000 grayscale images (28×28 pixels)
* Classes: Digits from **0 to 9**

---

## 🧠 Model Architecture

* Input Layer: 784 neurons (flattened 28×28 image)
* Hidden Layer: 128 neurons (ReLU activation)
* Output Layer: 10 neurons (Softmax activation)

---

## 🚀 Methodology

* Loaded and normalized image data
* Flattened images into vectors
* Applied one-hot encoding to labels
* Implemented forward propagation
* Computed loss using cross-entropy
* Performed backpropagation manually
* Updated weights using gradient descent

---

## 📊 Results

* Achieved ~94% test accuracy
* Loss decreases consistently over epochs
* Model correctly predicts handwritten digits

---

## 📌 Key Features

* Neural network implemented from scratch
* No high-level deep learning libraries used
* Demonstrates core concepts of backpropagation
* Educational and easy to understand

---

## 📌 Conclusion

The model successfully classifies handwritten digits using basic neural network principles. This project helps in understanding the internal working of deep learning models without relying on built-in frameworks.

---
