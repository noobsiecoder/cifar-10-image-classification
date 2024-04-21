# CIFAR-10 Image Classification with PyTorch

This repository contains code for performing image classification on the CIFAR-10 dataset using Convolutional Neural Networks (CNNs) implemented in PyTorch. The code is inspired by a Kaggle post by Shadab Hussain titled "CIFAR 10 - CNN using PyTorch" and has been adapted to a Jupyter Notebook format with CUDA acceleration.

### Overview

The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The task is to classify these images into one of the following classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

### Requirements

To run the code in this repository, you'll need:

- Python 3.x
- PyTorch
- Jupyter Notebook
- CUDA-enabled GPU (optional, but recommended for faster training)

### Usage

```bash
# 1. Clone this repository
git clone https://github.com/your-username/cifar-10.git
cd cifar-10

# 2. Install the required dependencies
pip install -r requirements.txt

# Open the Jupyter Notebook
jupyter notebook main.ipynb
```

### Credits

- The original inspiration for this code comes from [Shadab Hussain's Kaggle post](https://www.kaggle.com/code/shadabhussain/cifar-10-cnn-using-pytorch/notebook) on CIFAR 10 - CNN using PyTorch.
- The CIFAR-10 dataset is provided by the Canadian Institute for Advanced Research (CIFAR).

### License

This code is provided under the [MIT License](LICENSE).
