# 🧠 CNN Image Classification with TensorFlow

This project implements a **Convolutional Neural Network (CNN)** for image classification using the **CIFAR-10** dataset on Kaggle. The model is built and trained using **TensorFlow** and evaluated on unseen test data.

---

## 📁 Dataset

- **Dataset Name**: [CIFAR-10](https://www.kaggle.com/competitions/cifar-10)
- **Classes**:
  - airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck
- **Image Shape**: 32x32 pixels, RGB

---

## 🧠 Model Architecture

- **Input Layer**: 32x32x3 RGB images
- **Convolutional Layer 1**: 32 filters (3x3) + ReLU + MaxPooling
- **Convolutional Layer 2**: 64 filters (3x3) + ReLU + MaxPooling
- **Convolutional Layer 3**: 128 filters (3x3) + ReLU + MaxPooling
- **Flatten Layer**
- **Fully Connected (Dense) Layer**: 128 units + ReLU
- **Output Layer**: 10 units + Softmax (for 10 classes)
- **Optimizer**: Adam
- **Loss Function**: Sparse Categorical Crossentropy

---


