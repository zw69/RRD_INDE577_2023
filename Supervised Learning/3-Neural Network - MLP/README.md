# Multilayer Perceptron (MLP) for Handwritten Digit Classification

## Introduction
The Multilayer Perceptron (MLP) is a versatile neural network used for various tasks, including image classification. It consists of interconnected layers and is capable of learning complex patterns in data through feedforward and backpropagation processes.

## Algorithm
- **Feedforward**: Input data passes through the network, undergoing weighted sum calculations and activation functions in each layer.
- **Backpropagation**: Network error is computed and used to adjust weights iteratively, minimizing error during training.

## Implementation
We implemented an MLP to classify handwritten digits from the MNIST dataset. Initially, accuracy was low (10.28%), but it improved to 87.69% by the 40th epoch. Training cost decreased from 0.0900 to 0.0195, indicating effective learning.

## Advantages and Disadvantages
- **Advantages**:
  - Versatility: MLPs can handle various tasks.
  - Non-linearity: They model complex relationships.
  - Feature Learning: MLPs learn relevant features.
  - Scalability: Can be scaled for complexity.
  
- **Disadvantages**:
  - Overfitting: Prone to overfitting with complex architectures.
  - Hyperparameter Sensitivity: Proper tuning is crucial.
  - Computational Intensity: Training can be computationally expensive.
  - Data Preprocessing: Data may require extensive preprocessing.
  - Lack of Interpretability: Understanding MLP decisions can be challenging.

This MLP demonstrates the potential for complex pattern recognition, offering room for further optimization and improvements.
