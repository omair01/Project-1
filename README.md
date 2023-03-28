# Project-1
CINIC 10
#CINIC-10 dataset consists of natural images that are similar to the CIFAR-10 dataset but with higher resolution and more diverse classes
#Pre-trained CIFAR-10 is loaded and then we removed the last layer of the model, freezed the layers, added a new output layer for CINIC-10
#Then model is trained on the CINIC-10 dataset and evaluated on the test set

#Problem Statement: The goal is to use pre trained model of CIFAR 10 dataset on a new dataset like CINIC 10 dataset to train a model that can accurately classify the images into one of 10 classes.
#The idea is to classify 270000 images into 10 categories like aeroplane, bus, ship, etc

#Refences have been takem from medium, hugging face and chatgpt
# Data set can be downloaded from https://datashare.ed.ac.uk/handle/10283/3192
