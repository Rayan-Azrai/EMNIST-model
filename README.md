# EMNIST Character Classification with PyTorch

This project trains a neural network model using PyTorch to classify handwritten characters from the EMNIST dataset. The model consists of multiple fully connected layers with LeakyReLU activations. The repository includes code for data loading, training, evaluation, and visualization (loss curves, confusion matrix, and classification report).

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Overview

The goal of this project is to build a classifier for the EMNIST dataset—a dataset of handwritten characters. The model is trained using stochastic gradient descent with cross-entropy loss and is evaluated using standard classification metrics. This repository demonstrates:
- How to download and preprocess the EMNIST dataset using torchvision.
- How to build a neural network model in PyTorch.
- Training and evaluation procedures including loss monitoring and performance metrics.
- Visualization of training/validation loss curves and the confusion matrix.

## Installation

### Prerequisites
- **Python:** Version 3.7 or higher is recommended.
- **CUDA:** Optional, if you plan to run the model on a GPU.

### Dependencies

The project requires the following Python packages:
- `torch`
- `torchvision`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `pandas`

You can install these dependencies by running:
```bash
pip install -r requirements.txt
