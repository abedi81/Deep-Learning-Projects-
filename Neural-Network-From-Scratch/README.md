# Neural Network From Scratch: XOR and Decision Boundary Visualization

## Overview

This project implements a neural network from scratch using only NumPy to understand the core mechanics of deep learning.

The goal is to build, train, and visualize simple neural networks without relying on high-level libraries such as TensorFlow or PyTorch. The project focuses on forward propagation, backpropagation, weight updates, activation functions, loss tracking, and decision boundary visualization.

---

## Methodology

The project builds neural networks manually using:

- NumPy for matrix operations
- Custom activation functions
- Manual forward propagation
- Manual backpropagation
- Gradient-based weight updates
- RMS error tracking during training

Two architectures are implemented:

- One-hidden-layer neural network
- Two-hidden-layer neural network

---

## Model Architecture

### 1. Single Hidden Layer Network

The first model includes:

- Input layer
- One hidden layer
- Output layer

This model is trained on the XOR problem, a classic nonlinear classification task.

---

### 2. Two Hidden Layer Network

The second model extends the architecture by adding another hidden layer.

This allows the model to learn more flexible nonlinear decision boundaries and classify more complex patterns.

---

## Activation Functions

The project implements and compares:

- Sigmoid activation
- Tanh activation

Tanh is used in the final models because it helps the network learn nonlinear patterns more effectively in this setup.

---

## Training Process

The neural network is trained using:

- Forward propagation to compute predictions
- Backpropagation to calculate gradients
- Weight and bias updates using gradient descent
- RMS error to monitor learning progress

The loss decreases steadily during training, showing that the network successfully learns the target patterns.

---

## Decision Boundary Visualization

After training, random test points are generated and classified by the neural network.

The predicted classes are plotted to visualize the learned decision boundary.

This helps show how the network separates nonlinear regions in the feature space.

---

## Key Findings

- A neural network can learn nonlinear patterns such as XOR
- Backpropagation successfully reduces prediction error over training
- Adding hidden layers allows the model to learn more flexible decision boundaries
- Decision boundary plots provide an intuitive way to understand model behavior
- The loss curve confirms that training converges successfully

---

## Purposes of the Project


- How weights and biases are updated
- Why activation functions matter
- How hidden layers create nonlinear decision boundaries
- How neural networks learn through gradient descent

---

## Skills Demonstrated

- Neural networks from scratch
- Forward propagation
- Backpropagation
- Gradient descent
- Activation functions
- Nonlinear classification
- Loss visualization
- Decision boundary visualization
- NumPy-based deep learning implementation
