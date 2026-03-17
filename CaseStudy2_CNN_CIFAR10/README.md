# 🖼️ Image Classification using CNN (CIFAR-10)

## 📌 Overview

This project implements a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset into 10 different categories such as airplane, car, bird, cat, etc.

---

## ⚙️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib

---

## 📂 Dataset

* **CIFAR-10 Dataset**
* Contains 60,000 images (32x32 RGB)
* 10 Classes:

  * Airplane, Automobile, Bird, Cat, Deer
  * Dog, Frog, Horse, Ship, Truck

---

## 🧠 Model Architecture

* Convolutional Layers (Conv2D) for feature extraction
* MaxPooling layers for dimensionality reduction
* Flatten layer to convert features into vector
* Dense layers for classification
* Softmax activation for multi-class output

---

## 🚀 Methodology

* Loaded CIFAR-10 dataset from Keras
* Normalized pixel values (0–255 → 0–1)
* Built CNN model using Sequential API
* Trained model for 10 epochs
* Evaluated performance on test data
* Visualized predictions and accuracy

---

## 📊 Results

* Achieved ~71% test accuracy
* Training and validation accuracy plotted
* Model successfully predicts image classes

---

## 📌 Conclusion

The CNN model effectively learns image features and performs multi-class classification on CIFAR-10. Performance can be further improved using deeper architectures or data augmentation.

---
