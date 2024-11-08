# Fashion MNIST Classification with Neural Networks

This repository contains a project for classifying images from the **Fashion MNIST** dataset using a neural network built with TensorFlow and Keras. The model predicts the type of fashion item in each image, such as T-shirts, shoes, and bags.

## Project Overview

The goal of this project is to build a neural network model capable of recognizing different categories of fashion items in the Fashion MNIST dataset. This dataset is commonly used as a benchmark for image classification models, providing 10 classes of clothing items with 28x28 grayscale images.

## Dataset

The **Fashion MNIST** dataset contains 60,000 training images and 10,000 test images. Each image represents one of the following 10 categories:

- T-shirt/top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle boot

## Project Structure

- **Data Loading**: Loads the Fashion MNIST dataset directly from TensorFlow datasets.
- **Data Visualization**: Displays sample images along with their labels for quick inspection.
- **Data Preprocessing**: Scales image pixel values to the [0, 1] range to improve model performance.
- **Model Definition**: Defines a neural network with a fully connected dense layer.
- **Model Training**: Compiles and trains the model using the **Adam** optimizer and **sparse categorical cross-entropy** as the loss function.
- **Evaluation and Prediction**: Evaluates the model on the test dataset and displays test accuracy.
- **Visualization of Predictions**: Visualizes the predictions on sample test images along with prediction confidence.

## Requirements

Install the required packages using:

```bash
pip install tensorflow numpy matplotlib
