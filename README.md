# Neural Network from Scratch with NumPy

This project demonstrates the implementation of a simple two-layer neural network from scratch using only NumPy. The model is trained on the MNIST handwritten digit dataset and achieves **81% accuracy**.

---

## Project Overview

The neural network consists of:
- **Input Layer**: Accepts 784 features (28x28 pixels flattened).
- **Hidden Layer**: 100 nodes with ReLU activation.
- **Output Layer**: 10 nodes with softmax activation.

### Key Features
1. **Forward Propagation**: Computes predictions using matrix operations.
2. **Backward Propagation**: Updates weights and biases using gradient descent.
3. **NumPy Implementation**: The entire network is built without any machine learning libraries.

---

## Dataset

The [MNIST dataset](https://www.kaggle.com/competitions/digit-recognizer) contains 42,000 grayscale images of handwritten digits (0-9):
- **Training Set**: 41,000 images
- **Test Set**: 1,000 images

Each image is a 28x28 pixel matrix, flattened into a vector of size 784.

---

## Model Architecture

- **Hidden Layer**: 100 nodes, ReLU activation
- **Output Layer**: 10 nodes, Softmax activation
- **Loss Function**: Cross-Entropy Loss
- **Optimizer**: Gradient Descent

---

## Results

- **Accuracy on Test Set**: **81%**
- Simple yet effective model built without external deep learning libraries.

---

## Installation

1. Create a python enviroment with python 3.12
    ```bash
    python -m venv venv
    source venv/bin/activate
    ```
2. Install the required Python dependencies
    ```bash
    pip install numpy==2.2.0 pandas==2.2.3
    ```
3. Clone the repository:
    ```bash
    git clone https://github.com/AnantVerma-58/NN-from-Scratch
    ```
