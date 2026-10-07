# Deep Learning from Scratch

A step-by-step learning project that starts from a single neuron and gradually builds toward a complete neural network training pipeline using PyTorch.

## Overview

This repository documents my learning process in deep learning, starting from manual forward propagation and backpropagation, then moving to PyTorch, mini-batch training, and finally MNIST handwritten digit classification.

## Notebooks

### 01 - Single Neuron
- Manual forward pass
- ReLU activation
- Loss calculation
- Backpropagation
- Gradient descent
- Training loss visualization

### 02 - Small Neural Network
- 2 input features
- 2 hidden neurons
- 1 output neuron
- Manual multi-layer backpropagation
- Parameter updates
- Training loop

### 03 - PyTorch Version
- Rebuild the same neural network using PyTorch
- Automatic differentiation
- `loss.backward()`
- SGD optimizer
- Training loss visualization

### 04 - Mini-batch Training
- Multiple training samples
- Dataset and DataLoader
- Mini-batch training
- Comparison of batch sizes
- SGD vs mini-batch vs full-batch behavior

### 05 - MNIST Classification
- MNIST handwritten digit dataset
- 60,000 training images
- 10,000 test images
- Fully connected neural network
- Cross-entropy loss
- Mini-batch training
- Test accuracy
- Prediction visualization

## Technologies

- Python
- PyTorch
- Torchvision
- Matplotlib
- Jupyter Notebook

## Learning Path

Single Neuron  
→ Small Neural Network  
→ PyTorch  
→ Mini-batch Training  
→ MNIST Classification

The goal is to understand not only how to train neural networks with modern frameworks, but also what happens behind the scenes during forward propagation, backpropagation, and gradient descent.
