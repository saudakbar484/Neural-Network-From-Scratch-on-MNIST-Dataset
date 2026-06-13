# Neural Network From Scratch on MNIST Dataset

This project demonstrates a complete MNIST handwritten digit recognition pipeline using TensorFlow and Keras inside a polished Jupyter notebook.

## Project Overview

- Dataset: MNIST handwritten digits
- Approach: dense neural network built and trained in `ANN_3.ipynb`
- Model name: `saud_model`
- Highlights:
  - data loading and visualization
  - preprocessing and validation split
  - model architecture with dropout and ReLU activation
  - training with early stopping
  - evaluation and prediction visualization

## Notebook

- `ANN_3.ipynb`: contains the full project workflow and results

## Model Architecture

The model uses a feedforward neural network with:

- Flatten input layer
- Dense layer with 256 units, ReLU activation
- Dropout 0.2
- Dense layer with 128 units, ReLU activation
- Dropout 0.2
- Dense output layer with 10 units and softmax activation

## Usage

1. Open `ANN_3.ipynb` in Jupyter or VS Code.
2. Run all cells.
3. Review the training and evaluation results.

## Requirements

- Python 3.12+
- TensorFlow
- scikit-learn
- matplotlib

## Repository

This repository has been initialized and pushed to GitHub: https://github.com/saudakbar484/Neural-Network-From-Scratch-on-MNIST-Dataset
