# CIFAR-10 Image Classification using CNN (PyTorch)

A Convolutional Neural Network (CNN) built with **PyTorch** to classify images from the CIFAR-10 dataset. The model learns to recognize 10 different object categories from small 32×32 color images.

---

## 📌 Project Overview

This project implements a deep learning model using a **Convolutional Neural Network (CNN)** to perform image classification on the CIFAR-10 dataset. The model is trained using **PyTorch** and achieves good performance on the test dataset.

### Dataset: CIFAR-10

The CIFAR-10 dataset consists of **60,000 32x32 color images** across **10 classes**, with:

- 50,000 training images
- 10,000 testing images

Classes include:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

---

## 🧠 Model Architecture

The CNN model consists of:

- Convolutional layers for feature extraction
- ReLU activation functions
- MaxPooling layers for spatial downsampling
- Fully connected (Linear) layers for classification
- Softmax output for predicting class probabilities

Architecture Flow:
Input Image (32x32x3)
↓
Conv Layer + ReLU
↓
Max Pooling
↓
Conv Layer + ReLU
↓
Max Pooling
↓
Flatten
↓
Fully Connected Layers
↓
Output (10 Classes)

---

## 📊 Model Performance

| Metric | Score |
|------|------|
| Training Accuracy | **83.64%** |
| Testing Accuracy | **75.53%** |

The gap between training and testing accuracy indicates mild overfitting, which could be improved using techniques such as data augmentation, dropout, or regularization.

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/cifar10-cnn-pytorch.git
cd cifar10-cnn-pytorch