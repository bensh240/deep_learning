# CNN Classification with PyTorch

This notebook implements a complete convolutional neural network (CNN) using **PyTorch** for image classification on the **CIFAR-10** dataset. The assignment introduces automatic differentiation, model training pipelines, and evaluation using modern deep learning practices.

---

## Overview

This assignment builds on previous exercises and includes:

- Loading and normalizing the CIFAR-10 dataset using `torchvision`
- Defining CNN architectures using `torch.nn.Module`
- Using GPU acceleration with PyTorch when available
- Implementing training loops with SGD optimizers and loss functions
- Evaluating model performance and generating confusion matrices

This exercise emphasizes best practices, modular design, and proper use of the PyTorch framework.

---

## Guidelines and Requirements

- Ensure your code runs on both **CPU and GPU** environments.
- Follow best practices covered in class regarding model structure, loss handling, and training loops.
- Use appropriate visualizations and performance metrics.
- Do **not** change the cell structure unless instructed.
- Ensure code clarity, efficiency, and reproducibility.

---

## Environment Setup

### Required Libraries

- Python 3.6+
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- scikit-learn

To install dependencies, use the following:

```bash
pip install torch torchvision numpy matplotlib scikit-learn
