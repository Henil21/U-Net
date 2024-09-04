
# U-Net Using CNN

This repository contains the implementation of a U-Net model for image segmentation tasks using Convolutional Neural Networks (CNN). U-Net is a widely-used architecture in biomedical image segmentation due to its ability to learn from very few annotated images.

## Table of Contents
- [Introduction](#introduction)
- [Model Architecture](#model-architecture)


## Introduction
U-Net is a convolutional network architecture designed for fast and precise segmentation of images. The network architecture was initially developed for biomedical image segmentation but has since been applied to various other image segmentation tasks.

## Model Architecture
The U-Net architecture consists of two parts:
1. **Contracting Path (Encoder)**: A typical CNN architecture that extracts the context of the input image.
2. **Expanding Path (Decoder)**: A symmetric expansion path that enables precise localization.

The architecture is composed of:
- Convolutional layers
- MaxPooling layers
- UpSampling layers
- Skip connections between corresponding layers in the encoder and decoder paths.

![U-Net Architecture](https://upload.wikimedia.org/wikipedia/commons/2/2b/Example_architecture_of_U-Net_for_producing_k_256-by-256_image_masks_for_a_256-by-256_RGB_image.png)

## Installation
To get started, clone this repository and install the necessary dependencies.

```bash
git clone https://github.com/Henil21/U-Net.git
cd U-Net

