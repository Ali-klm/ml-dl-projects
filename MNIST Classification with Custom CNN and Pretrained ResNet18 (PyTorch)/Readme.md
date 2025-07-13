# MNIST Classification with Custom CNN and Pretrained ResNet18

This project demonstrates how to perform handwritten digit classification on the MNIST dataset using:

1. A simple convolutional neural network (CNN) implemented from scratch.
2. A pretrained ResNet18 model fine-tuned for MNIST.

## 🔧 Libraries Used

- PyTorch
- Torchvision
- HuggingFace `datasets`
- scikit-learn
- matplotlib & seaborn

## 🧪 Dataset

The MNIST dataset is loaded from the HuggingFace Hub:
- 60,000 training images
- 10,000 test images

## 📊 Features

- Custom `SimpleCNN` implementation
- Evaluation metrics: loss and accuracy
- Weight distribution visualization
- Transfer learning using pretrained ResNet18
- Training/Validation/Test loop implementation

## 🚀 How to Run

### Install dependencies:
```bash
pip install -r requirements.txt
