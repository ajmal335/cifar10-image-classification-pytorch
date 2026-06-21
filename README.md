# CIFAR-10 Image Classification using PyTorch CNN

## Project Overview

This project implements a Convolutional Neural Network (CNN) using PyTorch to classify images from the CIFAR-10 dataset.

The model uses:

- Convolutional Layers
- Batch Normalization
- ReLU Activation
- Max Pooling
- Dropout Regularization
- Data Augmentation
- Adam Optimizer

The model achieves approximately **74.8% test accuracy** on CIFAR-10.

---

## Dataset

CIFAR-10 contains 60,000 color images belonging to 10 classes:

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

Image size:

32 × 32 × 3 (RGB)

---

## Model Architecture

Input (3×32×32)

↓ Conv2D (3 → 32)

↓ BatchNorm

↓ ReLU

↓ MaxPool

↓ Dropout

↓ Conv2D (32 → 64)

↓ BatchNorm

↓ ReLU

↓ MaxPool

↓ Dropout

↓ Conv2D (64 → 128)

↓ BatchNorm

↓ ReLU

↓ MaxPool

↓ Dropout

↓ Flatten

↓ Dense (512)

↓ Dropout

↓ Output Layer (10 Classes)

---

## Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Scikit-learn
- Matplotlib

---

## Results

Test Accuracy: **74.8%**

---

## Future Improvements

- Transfer Learning with ResNet18
- Transfer Learning with ResNet50
- Hyperparameter Tuning
- Learning Rate Scheduling
- Data Augmentation Enhancements

---

## Author

Ajmal
Aspiring AI / Machine Learning Engineer
