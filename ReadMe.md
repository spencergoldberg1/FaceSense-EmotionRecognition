# Facial Recognition with AlexNet


<img src="https://img.shields.io/badge/Facial%20Recognition-AlexNet-blue.svg" alt="Facial Recognition">

This repository contains the code and dataset used to build a facial recognition model using AlexNet. The model is trained to recognize emotions and distinguish between happy and sad facial expressions.

## Motivation

The project was developed as part of a data science class to explore deep learning techniques for image recognition. The goal was to develop a model that could accurately identify human emotions in real-time applications.

## Dataset

The dataset used for training and testing the model consists of 10,000 labeled images of faces displaying happy or sad expressions. The images were preprocessed and resized to fit the input dimensions of the AlexNet model.

<img src="https://via.placeholder.com/150x150.png?text=Happy" alt="Happy Face">
<img src="https://via.placeholder.com/150x150.png?text=Sad" alt="Sad Face">

## Model Architecture

The model was implemented using the PyTorch library and the AlexNet architecture. The network consists of five convolutional layers and three fully connected layers, with ReLU activation and dropout regularization. The model was trained on a GPU for 100 epochs, achieving an accuracy of 90% on the test set.

## Usage

To use the facial recognition model, you can run the `predict.py` script with an input image file. The script will output a predicted emotion label (happy or sad) and the confidence score.
