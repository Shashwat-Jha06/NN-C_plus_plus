
# Neural Network from Scratch in C++

Welcome to the **Neural Network from Scratch in C++** project! This repository features a straightforward implementation of a neural network built entirely from the ground up using C++. Designed for AI and machine learning enthusiasts, this project provides insights into the mathematical and programming principles behind neural networks.

## Table of Contents

- [Overview](#overview)
- [Core Components](#core-components)
- [Architecture](#architecture)
- [Implementation](#implementation)
- [Example: XOR Operation](#example-xor-operation)
- [License](#license)
- [Citation](#citation)
- [Acknowledgments](#acknowledgments)

## Overview

This project implements a neural network from scratch using C++, without relying on external machine learning libraries. By building each component manually, we gain deeper understanding of how neural networks operate and learn from data. The implementation includes core building blocks like fully-connected layers, activation functions, loss functions, and gradient descent optimization.

## Core Components

The neural network implementation consists of:

- **Fully-connected (Linear) Layers**: Transforms input data through matrix multiplication and bias addition
- **Activation Functions**: Introduces non-linearity (Sigmoid, ReLU, Leaky ReLU, Tanh)
- **Loss Functions**: Measures prediction error (Binary Cross-Entropy, Mean Squared Error)
- **Gradient Descent**: Optimizes network parameters based on error gradients

## Architecture

The project uses a modular architecture with the following components:

- Base `Layer` class with derived implementations for different layer types
- A neural network (`NN`) class that manages layers and implements forward/backward propagation
- Utility functions for vector and matrix operations
- Activation and loss functions with their derivatives

The design allows for dynamic construction of neural networks with different architectures by adding various layer types.

## Implementation

The implementation features:

- **Vector and Matrix Operations**: Core mathematical operations for neural network computation
- **Parameter Initialization**: Random initialization for weights and biases
- **Forward Propagation**: Pass data through the network to generate predictions
- **Backward Propagation**: Update weights and biases based on prediction errors
- **Training Process**: Iterative optimization using gradient descent

## Example: XOR Operation

The repository includes an example demonstrating the neural network's ability to learn the XOR logical operation, which is not linearly separable. This example showcases how even a simple neural network can learn complex patterns that linear models cannot represent.

The XOR problem involves these input-output pairs:
- Input (0,0) → Output 0
- Input (0,1) → Output 1
- Input (1,0) → Output 1
- Input (1,1) → Output 0


## Acknowledgments

This project is inspired by the original work of Sorawit Chokphantavee and Sirawit Chokphantavee. We express our sincere gratitude for their foundational implementation and detailed explanations that made this adaptation possible.
