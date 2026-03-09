# Deep Learning Assignment 2: MNIST Handwritten Digit Classification

> **Academic Note**: This project was completed as part of the M.Sc. Cognitive Science curriculum (Course: Deep Learning).

## Project Overview
This assignment demonstrates the fundamental steps of building, training, and evaluating deep learning models for image classification. The primary objective is to classify handwritten digits (0-9) from the benchmark **MNIST dataset**.

## Methodology
The project explores two distinct neural network architectures to compare performance:
1.  **Fully Connected Neural Network (Dense)**: A baseline model using flattened input layers to learn global pixel patterns.
2.  **Convolutional Neural Network (CNN)**: An advanced model utilizing convolution and pooling layers to capture spatial hierarchies in the digit images.

## Technical Workflow
* **Data Preparation**: Loading the MNIST dataset and normalizing pixel values to a 0–1 range for faster convergence.
* **Model Implementation**: Built using the **Keras/TensorFlow** API.
* **Optimization**: Application of the Adam optimizer and cross-entropy loss functions.
* **Evaluation**: Achieving classification accuracies exceeding 95% on the test set.

## Implementation Details
* **Frameworks**: TensorFlow, Keras
* **Libraries**: NumPy, Matplotlib (for digit visualization)
* **Environment**: Jupyter Notebook



# Deep Learning Assignment 3: Advanced Neural Network Optimization

> **Academic Note**: This project was completed as part of the M.Sc. Cognitive Science curriculum (Course: Deep Learning).

## Project Overview
Following the foundational work in digital classification, this assignment focuses on advanced model tuning, regularization techniques, and the implementation of deeper architectural structures to improve generalization on unseen data.

## Key Objectives
* Implementing **Batch Normalization** and **Dropout** layers to prevent overfitting.
* Analyzing the impact of different activation functions (ReLU, Softmax) on model convergence.
* Visualizing training metrics (Accuracy/Loss curves) to diagnose model bias and variance.

## Methodology & Tools
* **Framework**: TensorFlow 2.19.0
* **Dataset**: MNIST / Custom image data processing.
* **Architecture**: Multi-layer Convolutional Neural Networks (CNNs).
* **Visualization**: Detailed plotting of model performance using Matplotlib to demonstrate learning stability.

## Requirements
To run this notebook, ensure you have the following installed:
```bash
pip install tensorflow numpy matplotlib pandas scikit-learn
