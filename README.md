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

## Installation

Clone the repository:

git clone https://github.com/yourusername/VAE-Image-Generation.git
cd VAE-Image-Generation

Install dependencies:

pip install tensorflow numpy matplotlib scikit-learn keras

Dataset Preparation

Place your dataset images inside the data/ directory.

The script automatically applies data augmentation to enhance the dataset.

Usage

Train the VAE model:

python train_vae.py --epochs 50 --batch_size 32

Generate new images using the trained model:

from model import generate_images
generate_images(num_images=5)

Model Architecture

Encoder: Convolutional layers reduce image dimensionality.

Latent Space: Mean and variance representations.

Decoder: Transposed convolution layers reconstruct images.
