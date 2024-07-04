# Tensor Decomposition Library

## Overview
This repository contains implementations of CP and Tucker tensor decompositions for optimizing convolutional layers in neural networks. The main focus is on decomposing the layers to reduce computational costs and memory usage, specifically for deep learning models like VGG16.

## Features
- CP (CANDECOMP/PARAFAC) Decomposition
- Tucker Decomposition
- Integration with PyTorch for convolutional layers

## Usage
The library provides functions for applying CP and Tucker decompositions to convolutional layers in neural networks. You can integrate these functions into your deep learning pipeline to optimize model performance and reduce memory usage.

## Requirements
Python 3.7+
PyTorch
TensorLy

## References
- [CP (CANDECOMP/PARAFAC) Decomposition](https://arxiv.org/pdf/1511.06530)
- [Tucker Decomposition](https://arxiv.org/pdf/1412.6553v3.pdf)
- [Integration with PyTorch for convolutional layers](https://arxiv.org/abs/1412.6553 )
