# Breast Cancer Prediction Model with PYTORCH

This repository contains a neural network model developed to predict breast cancer using the Wisconsin Breast Cancer dataset from scikit-learn. The model is trained to classify whether a tumor is benign or malignant based on several input features.

## Dataset Overview

    Dataset Name: Wisconsin Breast Cancer Dataset
    Source: Scikit-learn
    Number of Subjects: 569
    Features: 30 numeric features representing various characteristics of the cell nuclei present in the image.
    Target Variable:
        0: Malignant (Cancerous)
        1: Benign (Non-cancerous)
    Missing Values: None

## Feature Information

The dataset includes the following features:

    Radius (mean of distances from center to points on the perimeter)
    Texture (standard deviation of gray-scale values)
    Perimeter
    Area
    Smoothness (local variation in radius lengths)
    Compactness (perimeter^2 / area - 1.0)
    Concavity (severity of concave portions of the contour)
    Concave Points (number of concave portions of the contour)
    Symmetry
    Fractal Dimension ("coastline approximation" - 1)

Each feature has a mean, standard error, and "worst" (largest) value computed for each image, resulting in a total of 30 features.
Model Description
Technique

The model is a feedforward neural network implemented using PyTorch. The architecture includes the following components:

    Input Layer: 30 neurons corresponding to the 30 features.
    Hidden Layers: 3 hidden layers with ReLU activation functions.
    Output Layer: 1 neuron with a sigmoid activation function for binary classification.

Training

    Optimizer: Adam
    Loss Function: Binary Cross-Entropy
    Evaluation Metric: Accuracy
    Training/Test Split: 80% training, 20% testing

Tags

    Breast Cancer
    Neural Networks
    Binary Classification
    Healthcare
    Machine Learning
    Deep Learning
    scikit-learn
    Python
