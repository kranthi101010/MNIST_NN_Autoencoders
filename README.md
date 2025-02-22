# MNIST_NN_Autoencoders
Focus on MNIST classification and autoencoders.
Project: Exploring Neural Networks and Autoencoders on MNIST
Overview
This project explores different neural network architectures and autoencoders for handwritten digit classification using the MNIST dataset. We analyze the impact of model complexity, feature learning via autoencoders, and the effect of batch normalization and weight initialization.

Dataset
MNIST: A dataset of 60,000 training and 10,000 test grayscale images of handwritten digits (0-9), each of size 28x28 pixels.
Implemented Models
Softmax Classifier: A baseline model with only an input and output layer.
Naive Autoencoder: An autoencoder that learns to reconstruct MNIST digits.
Sparse Autoencoder: An autoencoder with sparsity constraints on activations.
Autoencoder-Based Classifier: A classifier that utilizes encoder features from the autoencoder.
Fully Connected Neural Network: A shallow neural network with a single hidden layer.
Deep Neural Network (5 Hidden Layers): Studying the effects of different weight initializations and batch normalization.
Experiments & Findings
Comparison of Classifiers: The sparse autoencoder-based classifier outperformed the naive autoencoder and softmax classifier.
Effect of Batch Normalization: Models with batch normalization converged faster and achieved higher accuracy.
Weight Initialization Impact: He initialization was most effective for ReLU activations.
Dependencies
Python 3.x
TensorFlow
NumPy
Matplotlib
How to Run the Project
