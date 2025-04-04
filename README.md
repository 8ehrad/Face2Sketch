# Sketch2Face and Face2Sketch Generative Models

## Overview
This project explores deep learning-based generative models for bidirectional image translation between sketches and realistic face images. The models leverage advanced neural networks to generate high-quality facial images from sketches and vice versa.

## Dataset
The dataset consists of paired face images and their corresponding sketches. It has been preprocessed to ensure optimal model training and evaluation.

## Model Architecture
We implemented and trained generative adversarial networks (GANs) to perform the sketch-to-face and face-to-sketch translations. The key components include:
- **Generator**: Transforms input images into the target domain.
- **Discriminator**: Differentiates between real and generated images.
- **Loss Function**: Adversarial loss along with additional reconstruction constraints.
