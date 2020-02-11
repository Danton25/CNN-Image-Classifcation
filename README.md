# Convolutional-NeuralNets
Create Neural Network and Convolutional Neural Network
### Task
This project is to implement neural network and convolutional neural network for the task of classifi- cation.
The classification task will be that of recognizing an image and identify it as one of ten classes. You are required to train the classifiers using Fashion-MNIST clothing images. Following are the three tasks to be performed:
1. Build a Neural Network with one hidden layer to be trained and tested on Fashion-MNIST dataset. Code from scratch in Python.
2. Build multi-layer Neural Network with open-source neural-network library, Keras on Fashion- MNIST dataset.
3. Build Convolutional Neural Network (CNN) with open-source neural-network library, Keras on Fashion-MNIST dataset.
### Dataset
For training and testing of our classifiers, we will use the Fashion-MNIST dataset. The Fashion-MNIST is a dataset of Zalando’s article images, consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes.
Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255. The training and test data sets have 785 columns. The first column consists of the class labels, and represents the article of clothing. The rest of the columns contain the pixel-values of the associated image.Each training and test example is assigned to one of the labels as show below,

T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle Boot
