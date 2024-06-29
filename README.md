# Neural Network from scratch Using Numpy and Pandas 

This notebook serves as a step-by-step tutorial on building a neural network using only NumPy and Pandas, focusing on the MNIST dataset. 

## Overview

We will construct a neural network from scratch using only fundamental Python libraries like NumPy and Pandas. The neural network will be trained on the MNIST dataset, which contains handwritten digits. The architecture of the neural network will consist of a single hidden layer with 20 hidden units and an output layer with 10 units corresponding to the 10 possible classes (digits 0 through 9).

## Key Components

- **Data Preprocessing**: We will preprocess the MNIST dataset using Pandas and NumPy, ensuring that the input matrix X has examples stacked in columns.

- **Neural Network Architecture**: The neural network will consist of an input layer, a hidden layer with 20 units, and an output layer with 10 units. We will explain the mathematical formulation of each layer and the activation functions used.

- **Forward Propagation**: We will demonstrate the forward propagation process, where input data is passed through the neural network to produce predictions. Each step of the forward propagation will be explained with relevant mathematical equations.

- **Backward Propagation**: The backpropagation algorithm will be explained in detail, showing how gradients are calculated for updating the model parameters (weights and biases). 

- **Loss Function**: We will use categorical cross-entropy as the loss function, which measures the difference between predicted probabilities and true labels.
