# Handwriting Recognition using CNN

This repository contains code for handwriting recognition using Convolutional Neural Networks (CNN). The implementation is based on deep learning models to classify writers based on their individual writing styles. The IAM Handwriting Dataset is utilized for training and testing the models. 

## Dataset and Preprocessing

The IAM Handwriting Dataset is a collection of handwritten text samples from various writers. For this project, a subset of the dataset containing data from 50 writers is used to prevent overfitting. Each writer is provided with a set of sentences, and each sentence is processed individually for analysis.

## Model Architecture

The handwriting recognition model is built using Keras with TensorFlow as the backend. The model architecture revolves around Convolutional Neural Networks (CNNs). It is worth noting that this model is language-independent, as it does not focus on individual letters or words but rather on patches of images extracted from the handwritten samples. Each image patch is resized to 113x113 pixels and fed into the CNN for learning.

## Usage

To use this repository:
1. Clone the repository to your local machine.
2. Ensure you have the necessary dependencies installed, including Python, TensorFlow, Keras, and any other required libraries.
3. Prepare the IAM Handwriting Dataset or use the provided subset of the dataset.
4. Run the notebook or script containing the CNN model implementation.
5. Train the model on the dataset and evaluate its performance.
6. Fine-tune hyperparameters and experiment with different architectures for potential improvements.


