# Neural Network From Scratch

A fully manual implementation of a feedforward neural network built **entirely from scratch** using **NumPy**.  
This project is designed to deepen understanding of neural network fundamentals by building every component step by step: layers, activations, losses, backpropagation, and training loops.

---

##  Project Overview

This repository contains a from-first-principles neural network implementation that mirrors the internal mechanisms of modern deep learning libraries. The project aims to:

- demystify how neural networks actually work under the hood  
- provide a clean and modular NumPy-based codebase  
- help others learn the math and code behind forward & backward propagation  
- evolve into a minimal deep learning framework

The project is a **work in progress** but already implements the core building blocks of a neural network.

---

##  Features Implemented

### ✔ Layers
- `LayerDense`: Fully-connected (linear) layer  
- Weight initialization  
- Bias initialization  
- Forward pass  
- Backpropagation (gradients for weights, biases, inputs)

### ✔ Activation Functions
- `ReLU`  
- `Softmax` (numerically stable implementation)

### ✔ Loss Functions
- Base `Loss` class  
- `LossCategoricalCrossentropy`  
- Loss calculation with clipping for numerical stability  
- Gradient computation

### ✔ Combined Modules
- `ActivationSoftmaxLossCategoricalCrossentropy`:  
  Optimized softmax + cross-entropy backward pass (faster and simpler)

### ✔ Forward Pass Pipeline
- Multiple layer architecture  
- Softmax probability outputs  
- Loss evaluation  

---

## In Progress

### Coming next:
- Full backpropagation for training  
- Training loop with batch updates  
- Accuracy tracking  
- Mini-batch gradient descent  
- Optimizers: SGD, Momentum, RMSprop, Adam  
- A high-level `Model` class to manage layers, training, and evaluation  
- Visualization (decision boundaries, loss curves)



