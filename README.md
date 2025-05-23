# Image Classification using CNN – Codetech Internship Task 3

This repository contains a solution for performing image classification using a Convolutional Neural Network (CNN). The objective is to classify handwritten digits from the MNIST dataset using TensorFlow.

---

## 📚 Dataset

The dataset used is **MNIST**, which includes:

- 60,000 training images
- 10,000 test images
- Images are grayscale, size 28x28 pixels
- 10 classes representing digits from 0 to 9

Example image:  
(Each sample is a handwritten digit like `5`, `3`, `0`, etc.)

---

## 💡 Project Overview

The project builds a Convolutional Neural Network (CNN) model using TensorFlow to classify images of digits. It includes:

- Preprocessing image data (normalization and reshaping)
- Building a CNN architecture using Keras (`Conv2D`, `MaxPooling2D`, `Dense` layers)
- Training the model with validation accuracy tracking
- Evaluating the model on unseen test data
- Visualizing training and validation accuracy

---

## ✅ Final Output

- **Test Accuracy:** ~99.02%
- Accuracy and loss visualized using Matplotlib

---

## 🔧 Requirements

Before running the code, make sure you have the following installed:

- Python 3.10+
- Libraries:
  - `tensorflow`
  - `matplotlib`
  - `numpy`

Install the dependencies using pip:

```bash
pip install tensorflow matplotlib numpy
