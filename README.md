# Deepfake Detection using Transfer Learning

A deep learning project focused on detecting GAN-generated deepfake images using transfer learning with multiple CNN architectures.

---

## 📌 Overview

This project evaluates multiple pre-trained convolutional neural networks to identify manipulated facial images.  

The goal was to compare model performance across architectures and determine which model generalizes best on a large-scale dataset.

---

## 📊 Dataset

- ~140,000 images (Real + Fake)
- Binary classification: Real vs Deepfake
- Preprocessing included:
  - Image resizing
  - Normalization
  - Data augmentation (rotation, flip, zoom)

> Dataset not uploaded due to size constraints.

---

## 🧠 Models Evaluated

The following transfer learning architectures were fine-tuned:

- VGG16  
- ResNet50  
- XceptionNet  
- EfficientNetB0  

All models were:
- Initialized with ImageNet weights
- Fine-tuned on custom dataset
- Trained with binary cross-entropy loss
- Evaluated using accuracy and validation metrics

---

## 🏆 Best Performing Model

**ResNet50** achieved the best validation performance after fine-tuning.

Example Results (replace with your actual numbers):

- Validation Accuracy: 94%
- Training Accuracy: 96%
- Improved generalization compared to VGG16

---

## ⚙️ Tech Stack

- Python  
- TensorFlow / Keras  
- PyTorch (if used)  
- CNNs  
- Transfer Learning  
- Data Augmentation  
- Matplotlib / Visualization  

---

## 📁 Repository Structure
