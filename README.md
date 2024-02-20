# Image Classification with Convolutional Neural Networks (CNN)

Welcome to my image classification project using CNNs! This repository contains code for training a Convolutional Neural Network to classify images into various categories. The CNN architecture used here is designed to effectively learn hierarchical features from images for accurate classification.

## Table of Contents
1. [Introduction](#introduction)
2. [CNN Overview](#cnn-overview)
3. [Math Behind CNN](#math-behind-cnn)

## Introduction
Image classification is a common task in computer vision, and CNNs have proven to be highly effective in this domain. This project demonstrates the use of CNNs to classify images into predefined categories, showcasing their ability to automatically learn relevant features from the data.

## CNN Overview
Convolutional Neural Networks (CNNs) are a class of deep learning models designed for processing structured grid data, such as images. They consist of convolutional layers, pooling layers, and fully connected layers, allowing them to efficiently learn hierarchical features from input data.

## Math Behind CNN
### Convolution Operation:
The convolution operation involves applying a filter (also known as a kernel) to the input image to extract features. Mathematically, it can be expressed as follows:
$(I * K)(i, j) = Σₘ Σₙ I(i + m, j + n) * K(m, n)$

where $I$ is the input image and $K$ is the filter.

### Pooling Operation:
Pooling layers downsample the spatial dimensions of the input. The max pooling operation, for example, can be represented as:
$MaxPooling(I)(i, j) = \max_{m, n} I(2i + m, 2j + n)$

### Fully Connected Layer:
The fully connected layer computes the final output by connecting every neuron to every neuron in the previous layer. Mathematically, it can be expressed as:
$Y = \sum(WX + b)$
where $W$ is the weight matrix, $X$ is the input vector, $b$ is the bias, and $sigma$ is the activation function.

These mathematical operations are performed during the forward pass to train the CNN.
