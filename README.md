# Handwritten Digit Classification with Convolutional Neural Networks

## Overview
This project implements a Convolutional Neural Network (CNN) to classify handwritten digits from the load_digits dataset in sklearn, By leveraging the power of deep learning techniques, including Batch Normalization, this model achieves impressive accuracy in recognizing digits from images, showcasing the effectiveness of CNNs in image classification tasks.

## Features
- Convolutional Layers: The model uses convolutional layers to automatically learn spatial hierarchies of features from the input images.
- Batch Normalization: Incorporated after convolutional layers to normalize activations and improve training speed and stability.
- Max Pooling: Utilized to down-sample feature maps, reducing the dimensionality and allowing the model to focus on the most salient features.
- Fully Connected Layers: The final classification is performed using fully connected layers, leading to a final softmax output for digit classification.

## Dataset
The project utilizes the load_digits dataset from sklearn, which contains 8x8 pixel images of handwritten digits (0-9). The dataset consists of 1,797 samples, each labeled with the corresponding digit.

## Installation

To run this project, ensure you have Python installed along with the following libraries:
```
pip install torch torchvision scikit-learn matplotlib numpy
```

## usage
1. clone this repository
```
git clone https://github.com/mobin-abdi/handwritten-numbers-classification
cd handwritten-numbers-classification
```

2. run
note: you should install jupyter-notebook with pip install jupyter-notebook and open cnn.ipynb with jupyter and run it


## Results

The model demonstrates a high classification accuracy on the test set, effectively distinguishing between the digits. Batch Normalization plays a crucial role in improving the convergence speed and performance of the model.

## Future Work

- Hyperparameter Tuning: Experiment with different architectures, learning rates, and batch sizes to find the optimal configuration.
- Data Augmentation: Introduce data augmentation techniques to enhance model robustness and prevent overfitting.
- Transfer Learning: Explore the use of pre-trained models for improved performance on more complex datasets.

## Acknowledgments
[PyTorch](https://pytorch.org/) for providing a flexible and powerful deep learning framework.

[scikit-learn](https://scikit-learn.org/) for the load_digits dataset and various machine learning tools.

### NOTE: The model will be trained on the load_digits dataset and will output training and testing accuracy after each epoch.
