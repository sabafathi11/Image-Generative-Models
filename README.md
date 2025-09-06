# Image Generative Models

This repository contains the implementation of various generative models for image generation, including Variational Autoencoders (VAE), Generative Adversarial Networks (GAN), and Denoising Diffusion Probabilistic Models (DDPM). The project is part of a Bachelor's thesis focused on image generation, with a particular emphasis on diffusion-based models and their applications.

## Overview

Generative models have revolutionized the field of computer vision by enabling the creation of realistic synthetic images. This repository explores three fundamental approaches to image generation:

- **Variational Autoencoders (VAE)**: Probabilistic models that learn to encode images into a latent space and decode them back
- **Generative Adversarial Networks (GAN)**: Adversarial training framework with generator and discriminator networks
- **Denoising Diffusion Probabilistic Models (DDPM)**: State-of-the-art diffusion-based models that generate images through iterative denoising

## Models Implemented

### 1. Variational Autoencoder (VAE)
A probabilistic generative model that learns a latent representation of images and can generate new samples by sampling from the learned distribution.

### 2. Generative Adversarial Network (GAN)
An adversarial training framework where a generator network learns to create realistic images while a discriminator network learns to distinguish real from generated images.

### 3. Denoising Diffusion Probabilistic Model (DDPM)
A diffusion-based model that generates images by learning to reverse a noise corruption process, producing high-quality samples through iterative denoising.

## Comparing Models

When comparing VAEs, GANs, and DDPMs, we evaluate performance using FID (lower is better), precision (fraction of realistic generated samples), and recall (coverage of real data diversity).You can see the detailed comparison results in the repository.

## Bachelor's Thesis Context
This implementation is part of a Bachelor's thesis research focused on:

- Comparative analysis of generative models
- Deep dive into diffusion-based models
- Applications and future directions in image generation

**[Read the complete thesis here](https://drive.google.com/file/d/1ca2HQaZm8X60L6wm9ASE15xaX4-qwwn4/view?usp=drive_link)**
