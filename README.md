# Fashion-MNIST

A comparison of a basic Deep Learning model and a CNN model on the fashion-MNIST dataset.

## Table of Contents
* [General Info](#generalinfo)
* [Technology Used](#technology)
* [Shallow Neural Network](#deeplearning)
* [Using CNN](#cnn)
* [Saving Model](#saving)
* [Conclusion](#conclusion)

## General Info
Fashion-MNIST is a dataset of Zalando's article images - consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes.

## Technology Used
* Tensorflow 2.0.0
* Python 3.7

## Shallow Neural Network
Libraries Used:
* numpy
* pandas
* keras
* matplotlib

A simple deep learning model having 2 hidden layers and an output layer was developed and trained for 5 epochs. The model performed adequately well on the test set with a test acuuracy of 87.47%.

## Using CNN
CNN is a class of deep neural networks most commonly applied to analyzing visual imagery. They are also known as shift invariant or space invariant neural networks, based on their shared weights architecture and translation invariance characteristics.

Each input image passed through a series of convolution layers with filters (Kernals), Pooling, fully connected layers (FC) and apply Softmax function to classify the object with probabilistic values between 0 and 1.

The model is trained for 10 epochs. The model achieves a test accuracy of 90.63%.

## Saving Model
We sometimes need to restore the model with other models, to test the model on a new data. There are two ways we can do this:
1. Saving model weights
2. Saving the entire model

Both of these methods have been depicted in this notebook.

## Conclusion
We reach the conclusion that a CNN is better at extracting features from image data. The accuracy jumped up by 3.16% when CNN was employed. The model can further be improved by using image augmentation, increasing the number of layers and epochs.
