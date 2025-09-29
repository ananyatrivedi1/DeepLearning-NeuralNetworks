# Deep Learning Foundations: Python Basics & Neural Network Fundamentals

This repository contains two foundational Jupyter notebooks that introduce key concepts in deep learning and neural networks using Python and NumPy.

## 📁 Files Overview

### 1. Python_Basics_with_Numpy.ipynb
**Purpose**: Master essential Python and NumPy operations for deep learning applications

**What I Accomplished**:
- Implemented fundamental functions using NumPy for efficient vectorized operations
- Built sigmoid functions and derivatives for activation functions
- Created image preprocessing utilities (flattening, normalization)
- Developed vectorized loss functions (L1 and L2)
- Practiced array reshaping and broadcasting techniques

**Key Functions Implemented**:
- `sigmoid()` - Vectorized sigmoid activation function
- `sigmoid_derivative()` - Gradient computation for backpropagation
- `image2vector()` - Convert 3D image arrays to 1D vectors
- `normalize_rows()` - Row-wise normalization for better convergence
- `softmax()` - Multi-class classification activation function
- `L1()` and `L2()` - Loss functions for model optimization

### 2. Logistic_Regression_with_a_Neural_Network_mindset-1.ipynb
**Purpose**: Build a complete logistic regression model from scratch using neural network principles

**What I Accomplished**:
- Constructed a binary classifier to distinguish cats vs non-cats in images
- Implemented forward and backward propagation algorithms
- Built optimization loops with gradient descent
- Applied the model to real image datasets (209 training, 50 test samples, 64x64 RGB images)

**Dataset Details**:
- Training images: 209 samples of 64x64 RGB images (flattened to 12,288 features)
- Test images: 50 samples with same dimensions
- Binary classification: Cat (1) vs Non-cat (0)

**Core Implementation**:
- Data preprocessing and standardization
- Forward propagation with sigmoid activation
- Cost function computation (logistic loss)
- Backward propagation for gradient calculation
- Parameter optimization using gradient descent
- Model evaluation and prediction

## 🛠️ Technologies Used

- **Python 3** - Primary programming language
- **NumPy** - Vectorized mathematical operations and array handling
- **Matplotlib** - Data visualization and image display
- **Jupyter Notebook** - Interactive development environment

## 🎯 Learning Objectives Achieved

- **Vectorization**: Eliminated for-loops using NumPy's broadcasting capabilities
- **Neural Network Fundamentals**: Understanding of forward/backward propagation
- **Optimization**: Gradient descent implementation from scratch
- **Image Processing**: Converting and preprocessing image data for ML models
- **Mathematical Foundations**: Implementing core ML mathematical operations

## 📊 Key Outcomes

Through these exercises, I gained hands-on experience with:
- Building ML models from mathematical first principles
- Efficient array operations using NumPy
- Understanding the computational graph of neural networks
- Preprocessing real-world image data for classification tasks

These notebooks serve as the foundation for more advanced deep learning concepts, providing practical experience with the mathematical and programming concepts that underpin modern neural networks.