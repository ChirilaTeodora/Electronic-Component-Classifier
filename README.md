# Electronic Component Classifier

A deep learning model built to automatically classify standard electronic components from images. The model relies on transfer learning using the MobileNetV2 architecture to achieve high accuracy with a lightweight footprint.

## Overview
This project was developed to automate the visual identification of basic hardware parts. It categorizes images into four main classes: 
* **Capacitors**
* **Inductors**
* **Resistors**
* **Transistors**

## Technical Details
* **Architecture:** MobileNetV2 (Transfer Learning)
* **Environment:** Model training and evaluation were performed in Google Colab to leverage GPU acceleration, while local testing routines were managed in Spyder.
* **Tech Stack:** Python, TensorFlow/Keras, NumPy, Matplotlib.

## Features
* **Transfer Learning Pipeline:** Reuses pre-trained ImageNet weights on MobileNetV2, fine-tuning the top layers for the specific electronic component dataset.
* **Image Preprocessing:** Includes data augmentation and normalization suited for MobileNetV2 input requirements.
* **Performance Evaluation:** Generates accuracy/loss curves and confusion matrices to validate model performance across all four hardware categories.
