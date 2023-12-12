# Single Neuron Model - The Perceptron

## Introduction

Welcome to the Perceptron project! In this Jupyter notebook, we delve into the Perceptron, a fundamental machine learning model renowned for its simplicity and effectiveness in binary classification tasks.

The Perceptron is a single-layer linear classifier that excels in scenarios where data separation is linear and the classification decision is clear-cut.


## Dataset and Problem Statement

For this project, we will utilize the "housing price dataset," which contains various factors related to house attributes such as area, bedrooms, bathrooms, proximity to the main road, and more.

### Problem Simplification

Although the Perceptron is primarily designed for classification problems, we will demonstrate its application to a simplified version of the dataset. Specifically, we will classify houses as "high-priced" or "low-priced" based on a threshold.

We will focus on a subset of features, including 'area,' 'bedrooms,' 'bathrooms,' 'mainroad,' and 'airconditioning.' Binary features like 'mainroad' and 'airconditioning' will be converted to integers for processing.

## Implementation

In this notebook, we'll perform the following key steps:

1. Load and preprocess the housing price dataset.
2. Convert the problem into a binary classification task.
3. Select a subset of features for simplicity.
4. Split the dataset into training and testing sets.
5. Implement the Perceptron class with training and prediction functionalities.
6. Train the Perceptron on the training data.
7. Evaluate the model's performance using accuracy, precision, recall, and a confusion matrix.
8. Visualize the decision regions and analyze the error over epochs.

## Conclusion

The Perceptron, despite its simplicity, demonstrates promising performance in classifying houses based on their price categories. This foundational model serves as an essential building block in machine learning and neural networks. Further enhancements and feature engineering could lead to improved accuracy and the development of more complex models for the housing price prediction task.

Feel free to explore the notebook, experiment with hyperparameters, and gain insights into the Perceptron's capabilities and limitations in binary classification.

Enjoy your exploration of the Perceptron model!
