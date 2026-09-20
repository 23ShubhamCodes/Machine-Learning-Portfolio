# MNIST Digit Classification using CNN

## Overview

This project implements handwritten digit classification
using a Convolutional Neural Network (CNN).

The model is implemented using TensorFlow and Keras.

## Dataset

The project uses the MNIST handwritten digit dataset.

The images are converted to grayscale pixel values and
normalized before being passed to the CNN.

## Model Architecture

The CNN consists of:

- Input Layer
- Convolutional Layer
- Max Pooling Layer
- Convolutional Layer
- Max Pooling Layer
- Flatten Layer
- Fully Connected Dense Layers
- Output Layer

## Technologies

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Convolutional Neural Networks

## Training

The model was trained for 10 epochs with a batch size of 64.

The Adam optimizer was used with sparse categorical
cross-entropy loss.

## Results

The model achieved approximately 94.1% accuracy on the
test set used in the experiment.

The project also includes:

- Training accuracy graph
- Validation accuracy graph
- Training loss graph
- Validation loss graph
- Sample predictions

## Sample Prediction

The notebook visualizes predicted and actual labels
for handwritten digit images.

## Project Structure

```text
01_MNIST_CNN_Classification/
│
├── README.md
└── MNIST_CNN_Classification.ipynb