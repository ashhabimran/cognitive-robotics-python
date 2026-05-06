# CNN CIFAR-10 Hyperparameter Tuning

## Overview

This project explores image classification using a convolutional neural network (CNN) trained on the CIFAR-10 dataset.

The notebook investigates how different hyperparameter configurations affect training and validation performance.

## Dataset

The project uses the CIFAR-10 dataset, which contains 60,000 colour images across 10 classes:
- 50,000 training images
- 10,000 test images
- 32x32 RGB image format

## Experiment

A simple CNN model was trained using different combinations of:

- Batch size: 64, 128, 256
- Epochs: 10, 20
- Learning rate: 0.001, 0.01
- Dropout rate: 0.25, 0.5

Each configuration was evaluated using training accuracy, validation accuracy, training loss, and validation loss.

## Results

The best validation accuracy achieved was approximately **68.24%**, using:

- Batch size: 128
- Epochs: 20
- Learning rate: 0.001
- Dropout rate: 0.25

The results suggest that a lower learning rate generally produced stronger validation performance, while higher learning rates led to weaker results across most configurations.

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Google Colab

## Notes

This project was originally developed in Google Colab as part of a university machine learning / cognitive robotics exercise.
