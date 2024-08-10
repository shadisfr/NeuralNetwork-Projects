# Autoencoder Reconstruction of Mixed MNIST and CIFAR-10 Images

## Introduction

In this practical assignment, you will explore autoencoders, a fundamental deep learning technique, to reconstruct images from two distinct datasets: MNIST and CIFAR-10. The goal is to build an autoencoder model that can take the mean of an MNIST and a CIFAR-10 image, process it, and generate reconstructions of both the MNIST and CIFAR-10 images.

## Task Overview

### 1. Image Selection
- Select a random image from the **MNIST** dataset and a random image from the **CIFAR-10** dataset.

### 2. Mean Image Computation
- Compute the mean of these two images element-wise.

### 3. MNIST Image Preparation
- **Resize** the MNIST image to match the dimensions of CIFAR-10 images.
- **Extend the channels** of the MNIST image to match the channels of CIFAR-10 images (from 1 to 3 channels).

### 4. Autoencoder Model Construction
- Build an autoencoder model using PyTorch.
- The **encoder** should compress the input image into a latent representation.
- The **decoder** should reconstruct the input image from the latent representation.

### 5. Model Training
- Train the autoencoder using the mean image computed earlier.
- Use a loss function like **Mean Squared Error (MSE)**.
- Optimize the model using an optimizer such as **Adam**.

### 6. Reconstruction
- Input the mean image into the trained autoencoder.
- Obtain reconstructions of both MNIST and CIFAR-10 images from the autoencoder.

### 7. Evaluation
- **Visually assess** the quality of the reconstructions.
- **Compare** the reconstructed MNIST and CIFAR-10 images with their originals.
- Use metrics like the **Structural Similarity Index (SSIM)** or **Peak Signal-to-Noise Ratio (PSNR)** for quantitative evaluation.

## Detailed Instructions

### 1. Dataset Preparation
- **Datasets**: Utilize the MNIST and CIFAR-10 datasets.
- **Image Properties**:
    - MNIST images: Grayscale (1 channel), 28x28 pixels.
    - CIFAR-10 images: RGB (3 channels), 32x32 pixels.

### 2. Mean Image Computation
- Randomly select one image from the MNIST dataset and one from the CIFAR-10 dataset.
- Compute the mean of these two images element-wise.

### 3. MNIST Image Preparation
- **Resize** the MNIST image to 32x32 pixels to match the CIFAR-10 image dimensions.
- **Channel Extension**: Convert the single-channel MNIST image to 3 channels to match the CIFAR-10 image format.

### 4. Autoencoder Model Construction
- Design an autoencoder architecture in PyTorch with the following components:
    - **Encoder**: Compress the input image into a lower-dimensional latent space.
    - **Decoder**: Reconstruct the image from the latent representation.

### 5. Model Training
- Train the autoencoder on the computed mean image.
- Use **Mean Squared Error (MSE)** as the loss function.
- Optimize the model using the **Adam** optimizer.

### 6. Reconstruction
- Feed the prepared mean image into the autoencoder.
- Obtain and save the reconstructions of both the MNIST and CIFAR-10 images.

### 7. Evaluation
- Visually inspect the quality of the reconstructed images.
- Compare the reconstructions with the original MNIST and CIFAR-10 images.
- For quantitative evaluation, consider using the **Structural Similarity Index (SSIM)** or **Peak Signal-to-Noise Ratio (PSNR)**.

## Expected Outcome

By the end of this project, you should achieve the following:
- A trained autoencoder capable of reconstructing images based on the mean of an MNIST and a CIFAR-10 image.
- Insights into how autoencoders learn and reconstruct mixed image inputs.
- Experience in applying deep learning techniques such as autoencoders in PyTorch.
