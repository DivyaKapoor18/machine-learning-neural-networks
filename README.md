# Neural Networks Assignment - Handwritten Digit Recognition

**Machine Learning Course Assignment | MNIST Classification with Keras**

This repository contains my implementation of a neural network for handwritten digit recognition using the MNIST dataset, completed as part of my Machine Learning course.

## 📋 Project Overview

This assignment demonstrates the implementation of a multi-layer perceptron (MLP) neural network using Keras/TensorFlow to classify handwritten digits from the famous MNIST dataset.

## 🏗️ Model Architecture

The neural network follows this architecture:
- **Input Layer**: Flatten layer converting 28×28 images to 1D arrays (784 neurons)
- **Hidden Layer 1**: Dense layer with 300 neurons, ReLU activation
- **Hidden Layer 2**: Dense layer with 100 neurons, ReLU activation  
- **Output Layer**: Dense layer with 10 neurons, Softmax activation (for 10-digit classification)

## 🚀 Quick Start

⚙️ Key Features
- Data preprocessing and normalization
- Sequential neural network model building
- Model training with 20 epochs
- Performance visualization and prediction testing
- Comprehensive model summary and analysis

📈 Model Performance
- The implemented neural network achieves:
- Effective digit classification on the MNIST dataset
- Proper learning curve demonstration over 20 epochs
- Clear visualization of predictions on test samples
  
### Prerequisites
```bash
pip install -r requirements.txt

