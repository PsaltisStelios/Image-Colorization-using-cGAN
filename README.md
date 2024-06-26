# Image-Colorization-using-cGAN

## Introduction
This project implements a cGAN-based approach for colorizing grayscale images. It leverages the power of deep learning to generate realistic and plausible color representations for black and white photos. If you're looking for a quick start with image colorization using cGANs, check out this great repository by Moein Shariatnia: Image Colorization Tutorial. My project builds upon this by offering a more in-depth explanation on pre-processing techniques, particularly finding L,a and b values  for weight initialization. Additionally, I introduce a new loss function that has shown to improve colorization results in my experiments.

## Features

Trains a cGAN model to learn the mapping between grayscale and color images.
Offers the ability to colorize your own grayscale images using the trained model.
(Optional) Provides visualizations of the training process and generated colorized images.

## Files in this repo and how to use ( Beginner Friendly Repo :D )

* Model.py: Sequential model architecture (Feel free to experiment as you like)
* Weights.h5: Weights and biases of our trained model (If you dont want to train the model yourself, you can implement this in the model architecture and see the magic happen!)
* requirements.txt: File listing the required Python libraries (You can install them by using "pip install -r requirements.txt"  in a new environment)
* LICENSE
* README.md: This file (you're reading it!).
