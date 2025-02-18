# Practical Session 2: Supervised Deep Learning

This repository contains the code on Supervised Deep Learning. The goal of this session is to experiment with different deep neural network models to classify images from a subset of the CIFAR10 dataset, which we call CIFAR4. The dataset consists of 24,000 images from 4 classes: BIRD, CAT, FROG, and HORSE.

## Dataset
The dataset is a subset of CIFAR10, containing only 4 classes. Each image is a 32x32 RGB image, resulting in an input tensor of size [32, 32, 3]. The dataset is available on eCampus.

## Objectives
- Train different deep neural network models to classify images into one of the 4 classes.
- Experiment with Multi-Layer Perceptron (MLP) and Convolutional Neural Network (CNN) architectures.
- Understand the importance of train/validation/test splits and the role of validation data during training.
- Explore techniques to prevent overfitting and improve model performance.


## Key Concepts
- **Train/Validation/Test Split**: The dataset is split into training, validation, and test sets to evaluate the model's performance on unseen data.
- **Overfitting**: Techniques such as dropout, regularization, and data augmentation are used to prevent overfitting.
- **Model Comparison**: The notebook compares the performance of MLP and CNN models on the image classification task.

## Results
- **MLP Model**: The MLP model achieves an accuracy of around 55-58% on the test set.
- **CNN Model**: The CNN model achieves an accuracy of around 76% on the test set, demonstrating the effectiveness of convolutional layers for image classification tasks.
