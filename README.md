# MNIST CNN Classifier

This project builds and trains a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify handwritten digits from the MNIST dataset.

---

## 🧠 Overview

The MNIST dataset is a standard benchmark in machine learning for image classification. It contains 70,000 grayscale images of handwritten digits (0–9), each of size 28x28 pixels.

This project uses:
- **Convolutional layers** for feature extraction
- **Max pooling** for downsampling
- **Dense layers** for classification
- **Sparse categorical crossentropy** as the loss function
- **Matplotlib** for visualizations

---

## 🚀 Features

- Uses **20% of training data as validation**
- Trains a CNN on the MNIST dataset
- Evaluates performance on the test set
- Plots **training and validation loss**
- Displays **20 random training images** with:
  - True and predicted labels
  - Green titles for correct predictions
  - Red titles for incorrect predictions

---

## 📦 Requirements

- Python 3.7+
- TensorFlow
- NumPy
- Matplotlib

Install dependencies with:

```bash
pip install tensorflow matplotlib numpy
