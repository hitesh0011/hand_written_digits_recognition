# MNIST Handwritten Digits Classification

## Overview
This project implements a **Neural Network model using TensorFlow and Keras** to classify handwritten digits from the **MNIST dataset**. The model is trained on 60,000 images and tested on 10,000 images. It achieves high accuracy in recognizing digits (0-9) with a simple feedforward architecture.

## Dataset
The project uses the **MNIST dataset**, which consists of:
- 60,000 training images
- 10,000 testing images  
Each image is a **28x28 grayscale digit**.

## Model Architecture
The neural network is built using TensorFlow's Keras API with the following layers:
- **Input Layer:** 784 neurons (flattened 28x28 images)
- **Hidden Layer:** 100 neurons with ReLU activation
- **Output Layer:** 10 neurons with sigmoid activation (for classification)

## Technologies Used
- **Python**
- **TensorFlow/Keras**
- **NumPy**
- **Matplotlib**
- **Seaborn** (for visualization)

## Installation
Clone the repository and install dependencies:
```sh
git clone https://github.com/your-username/mnist-classification.git
cd mnist-classification
pip install tensorflow numpy matplotlib seaborn
