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

### Prerequisites
```bash
pip install -r requirements.txt
