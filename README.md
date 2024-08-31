# GAN Digit Generator

This repository contains a Generative Adversarial Network (GAN) implementation using PyTorch to generate handwritten digit images similar to those in the MNIST dataset.

## Overview

The GAN model consists of a generator and a discriminator, trained adversarially. The generator creates digit images from random noise, while the discriminator attempts to distinguish between real MNIST digits and generated ones. 

## Model Architecture

- **Generator:** A simple feedforward network with transposed convolutional layers to upscale random noise into a 28x28 grayscale digit image.
- **Discriminator:** A convolutional network that classifies 28x28 images as real or fake.

## Training

The training process involves iteratively updating the generator and discriminator using a standard GAN loss. The generator learns to produce increasingly realistic digits, while the discriminator improves its ability to differentiate between real and generated images.

## Results

After training, the generator can produce realistic-looking digit images, showcasing the effectiveness of the GAN model.

## Usage

To generate new digits, simply run the provided script and observe the generated outputs saved in the specified directory.
