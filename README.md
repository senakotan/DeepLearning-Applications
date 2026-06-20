# DeepLearningApplications

This repository contains three deep learning projects developed as part of the **Introduction to Deep Learning** course.

The project covers computer vision, natural language processing, and unsupervised learning using TensorFlow/Keras.

## Projects

### 1. CNN for CIFAR-10 Image Classification
A Convolutional Neural Network (CNN) was trained on the CIFAR-10 dataset to classify images into 10 object categories.

**Results**
- Test Accuracy: 78.74%
- Macro Precision: 0.8002
- Macro Recall: 0.7874
- Macro F1-Score: 0.7849

### 2. Bidirectional LSTM for IMDB Sentiment Analysis
A Bidirectional LSTM model was used to classify movie reviews as positive or negative.

**Results**
- Test Accuracy: 83.70%
- Macro F1-Score: 0.8368
- AUC-ROC: 0.9145

### 3. Denoising Autoencoder for MNIST
A convolutional denoising autoencoder was trained to reconstruct clean handwritten digit images from noisy inputs.

**Results**
- MSE: 0.04657 → 0.00507
- PSNR: 13.32 dB → 22.95 dB
- MSE Reduction: 89.1%

---
## Technologies

- Python
- TensorFlow / Keras
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

## Datasets

- CIFAR-10
- IMDB Movie Reviews
- MNIST Handwritten Digits

## Environment

All experiments were conducted using Google Colab with GPU acceleration.

