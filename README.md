# Simple_CNN_for_Fashion-Mnist
This repository contains a Python script that trains a simple convolutional neural network (CNN) on the FashionMNIST dataset using PyTorch. The FashionMNIST dataset consists of images of 10 different types of clothing, such as sneakers and dresses, and the goal of the CNN is to classify these images into their respective classes.

The script first imports the necessary libraries, including PyTorch and torchvision for loading and preprocessing the data. It then loads the FashionMNIST training and test sets, and defines the dataloaders for them. The dataloaders allow the data to be processed in batches and shuffled during training.

Next, the script sets the seed for the random number generator to ensure reproducibility of the results. It also initializes the CNN, which consists of two convolutional layers followed by a fully connected layer, and an output layer. The convolutional layers use ELU activation functions and are followed by max pooling layers. The fully connected layer uses ELU activation and dropout regularization.

The script then defines an Adam optimizer and a cross entropy loss function, and trains the CNN on the training data for a specified number of epochs. The training loss and accuracy are printed for each epoch. Finally, the script tests the CNN on the test data and prints the test loss and accuracy.
