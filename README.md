# Variational Autoencoder for image generation
Variational Autoencoder (VAE) for Image Generation

## Overview

This project implements a Variational Autoencoder (VAE) using TensorFlow and Keras to generate images. The model learns a lower-dimensional representation of the input images and reconstructs them with minimal loss, making it ideal for applications like image generation, denoising, and anomaly detection.

## Key Features

✅ Encoder-Decoder Architecture for dimensionality reduction and reconstruction

✅ Reparameterization Trick to ensure differentiability during training

✅ Image Augmentation to enhance generalization

✅ Custom Loss Function combining reconstruction loss and KL divergence

✅ Training Pipeline using TensorFlow/Keras



## Model Architecture

Encoder: Convolutional layers reduce image dimensionality.

Latent Space: Mean and variance representations.

Decoder: Transposed convolution layers reconstruct images.
