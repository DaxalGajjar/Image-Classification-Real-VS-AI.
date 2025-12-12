# Image-Classification-Real-VS-AI.

Overview: This project detects whether an image is AI-generated or authentic using a convolutional-neural-network (CNN) with Xception as the backbone.
The notebook includes a complete end-to-end workflow:

1.Mount Google Drive
2.Install and import required libraries
3.Load training, validation, and test datasets
4.Apply preprocessing and augmentation
5.Build a transfer-learning model using Xception
6.Train the classifier
7.Evaluate test accuracy
8.Generate predictions and export results
9.Plot training metrics
10.This repository contains the full .ipynb code required to train and test the model.

Features

Binary classification (0 = AI, 1 = Real)
Uses TensorFlow Keras + Xception pretrained on ImageNet
Data augmentation (rotation, shear, zoom, flip, brightness)
Highly structured generator-based pipeline
Training, validation, and test separation using CSV metadata
Saves model (.h5 format)
Generates prediction CSV
Visualization of training curves (accuracy & loss)
