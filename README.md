# Vegetable_Classifier

## Overview:
Using deep learning to classify 15 classes of vegetables from a data set of 21000 from *Ahmed, M. Israk & Mamun, Shahriyar & Asif, Asif. (2021). DCNN-Based Vegetable Image Classification Using Transfer Learning: A Comparative Study. 235-243. 10.1109/ICCCSP52374.2021.9465499*. 

## Where to get dataset?
The data has a creative commons license. You can get it at [here](https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset?resource=download).

## Information about Convolution Neural Networks:

### Purpose of Convolution
Convolution is used to extract features. In terms of image classification instead of manually extracting feature, convolution allows us to extract features using a filter that will essentially match how close a group of pixels is to a filter.

### Activation Function
Output layer: Used to determine which neurons are *activated* or firing and based on which neurons are firing the classification can be made.

Hidden layer: The purpose of hidden layers is to model more complex data. Without activation functions a system composed of hidden layers will have an output that is a linear combination of the initial inputs, thus making the hidden layers redundant. Activation functions in the hidden layer help make the data non linear and helps model more complex data.

### Pooling:
Pooling is used to reduce the dimensions of the inputs. An added benefit of pooling is that it makes the neural network more general since it eliminates noise and generalizes the location and size of some features.