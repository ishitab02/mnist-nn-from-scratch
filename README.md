# MNIST Neural Network from Scratch 

This project implements a simple neural network from scratch using only **NumPy** to classify handwritten digits from the MNIST dataset, without relying on high-level machine learning libraries like **PyTorch** or **TensorFlow**

## Overview

- **Frameworks Used**: NumPy
- **Dataset**: MNIST (handwritten digits) from Kaggle
  
- **Model Architecture**:
  
-  The model consists of a NN with an input layer, one hidden layer and an output layer, all of which are computed using Mathematics- vector algebra and matrix operations
  - Input Layer: 784 neurons (28x28 pixels)
  - Hidden Layer: 128 neurons with ReLU activation
  - Output Layer: 10 neurons with Softmax activation
    
- **Training Details**:
  
  - Optimization: Mini-batch Gradient Descent
  - The network uses **ReLU activation** in the hidden layer and **Softmax activation** in the output layer.
