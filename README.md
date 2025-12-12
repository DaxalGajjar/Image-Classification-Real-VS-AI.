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

1.Binary classification (0 = AI, 1 = Real)
2.Uses TensorFlow Keras + Xception pretrained on ImageNet
3.Data augmentation (rotation, shear, zoom, flip, brightness)
4.Highly structured generator-based pipeline
5.Training, validation, and test separation using CSV metadata
6.Saves model (.h5 format)
7.Generates prediction CSV
8.Visualization of training curves (accuracy & loss)

Requirements

1 This notebook runs on Google Colab.
2 Install Dependencies
3 Colab already provides TensorFlow.
4 The notebook imports:
5 tensorflow
6 numpy
7 pandas
8 matplotlib
9 keras (from TensorFlow)
10 Xception pretrained model
No additional manual installation is required.

Use Cases

This model is useful for:
Image authenticity verification
Detecting deepfakes
Research projects on GAN fingerprinting
College/university computer vision assignments
Training further models for AI detection

Future Improvements

You may extend this project by:
1 Using EfficientNetV2, ViT, or ConvNeXt
2 Applying GAN fingerprint extraction
3 Building a complete API with FastAPI
4 Creating a mobile app for user-side classification
5 Expanding dataset size

