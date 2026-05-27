# Handwritten Digit Recognition Using Deep Learning

## Overview

This repository demonstrates a handwritten digit recognition pipeline using the MNIST dataset and a simple deep learning model built with TensorFlow and Keras.

The notebook `MNIST_Digit_Classification.ipynb` includes:
- dataset download and inspection
- visualizing sample handwritten digits
- preprocessing and normalization
- neural network model building with `Sequential`
- training, evaluation, and accuracy/loss plotting
- prediction visualization
- saving and loading the trained model

## Key Features

- Uses the MNIST dataset of 28x28 grayscale digit images
- Builds a feedforward neural network with dense layers and dropout
- Trains for 10 epochs using `adam` optimizer and categorical cross-entropy
- Saves the trained model to `mnist_digit_classifier.h5`

## Requirements

- Python 3.8+
- TensorFlow
- NumPy
- Matplotlib
- scikit-learn
- KaggleHub (optional for dataset download)

## Setup

1. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # on Windows use `venv\Scripts\activate`
   ```
2. Install dependencies:
   ```bash
   pip install tensorflow numpy matplotlib scikit-learn
   pip install kagglehub
   ```

## Running the Notebook

Open `MNIST_Digit_Classification.ipynb` in Jupyter Notebook or VS Code and run the cells sequentially.

If you want to skip KaggleHub, the notebook also loads the MNIST dataset directly from `tf.keras.datasets.mnist`.

## Notes

- The notebook saves the trained model as `mnist_digit_classifier.h5`.
- The notebook uses one-hot encoding for labels and normalizes the images to the `[0, 1]` range.

## License

This project is provided for educational purposes.

