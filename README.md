# Image-Classification
This project implements a binary image classification system that distinguishes between dogs and cats using a Convolutional Neural Network (CNN).
The goal of this project is to understand and apply deep learning concepts for image classification, including data preprocessing, CNN architecture design, training, evaluation, and prediction.
1.Model Architecture:
  The model follows a standard CNN pipeline:
    i. Convolutional Layers:
        -Extract spatial features from images
        -Learn edges, textures, and shapes
    ii. Activation Function: 
        -ReLU is used to introduce non-linearity
    iii. Pooling Layers:
        -Max Pooling reduces spatial dimensions
        -Helps prevent overfitting
    iv. Fully Connected Layers:
        -Flattened feature maps are passed to dense layers
        -Final layer outputs class probabilities

2.Dataset Description:
  -Dataset contains images of dogs and cats
  -Images are labeled and organized into respective classes
  -Dataset is not included due to size limitations

3.Data Preprocessing:
The following preprocessing steps are applied:
  -Image resizing to a fixed input size
  -Normalization of pixel values
  -Conversion of images into tensors
4.Training Process:
  i. Load and preprocess the dataset
  ii. Define the CNN architecture
  iii. Compile the model with:
        -Loss function: Binary Cross-Entropy
        -Optimizer: Adam
  iv. Train the model for multiple epochs
  v. Monitor training and validation accuracy and loss
5.Model Evaluation:
  -Accuracy and loss are evaluated on validation/test data
  -Training curves help analyze overfitting or underfitting
  -The model is tested on unseen images to verify generalization
6.Prediction:
  -The trained model can predict whether a given image is a Dog or a Cat.
