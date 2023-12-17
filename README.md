# Handwritten Digit Classification using CNN

## Overview

This project implements a Convolutional Neural Network (CNN) for handwritten digit classification. The model is trained on the MNIST dataset, which consists of 28x28 grayscale images of handwritten digits (0 through 9).

## Requirements

- Python 3.x
- TensorFlow
- NumPy
- Matplotlib (for visualization)

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/handwritten-digit-cnn.git
    cd handwritten-digit-cnn
    ```


## Usage

1. **Train the CNN model:**

    ```bash
    python train_model.py
    ```

2. **Evaluate the model:**

    ```bash
    python evaluate_model.py
    ```

3. **Make predictions on new images:**

    ```bash
    python predict_image.py path/to/your/image.png
    ```

## Results

The trained CNN achieved an accuracy of 99.16% on the test dataset. The Mean Absolute Error (MAE) is 0.84.

## Model Architecture

The CNN architecture consists of:

- Convolutional layers with ReLU activation
- MaxPooling layers for downsampling
- Dense layers with ReLU activation for classification


