# RNN Character Prediction

This repository contains a simple implementation of a Recurrent Neural Network (RNN) used for character prediction. The model learns to predict the next character in a sequence of characters based on training data. This example demonstrates the use of RNNs for a basic sequence prediction task.

## Table of Contents
- [Description](#description)
- [Usage](#usage)

## Description
This RNN model is built to predict the next character in a sequence, based on a small dataset of characters ('d', 'o', 'g', 's'). It uses a character-level prediction task, where each character in the sequence is mapped to a one-hot encoded vector.

The network consists of:
- An input layer with a one-hot encoded vector representing each character.
- A hidden layer with a tanh activation function.
- An output layer with a softmax activation function to predict the next character.

The model is trained using the cross-entropy loss function and backpropagation through time (BPTT).

## Usage

### 1. Clone the repository
To clone this repository to your local machine, use the following command:
`RNN.ipynb`
