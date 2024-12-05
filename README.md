# Assessment-for-Entry-Level-Junior-AI-ML-Engineer-at-Nagorik
# Fine-Tuning Stable Diffusion for Image-to-Image Generation

## Overview
This project demonstrates how to fine-tune a **Stable Diffusion model** for **image-to-image generation** tasks. The goal is to train a model that takes an input image (source) and generates a transformed output image (target). We apply various transformations, such as rotations, to the target images in order to fine-tune the model. Once the model is fine-tuned, it can generate target images for new input images.

## Key Features
- **Dataset Preparation**: The dataset consists of source and target images. Transformations like rotation are applied to the target images.
- **Fine-Tuning**: A pre-trained Stable Diffusion model is fine-tuned using the prepared dataset to generate the target image based on the source image.
- **Testing**: After fine-tuning, the model is tested on new source images to generate the corresponding target images.

## Requirements
To run this project, you'll need to install the following dependencies:

- **Python 3.x**
- **PyTorch**
- **Hugging Face `transformers` and `diffusers`**
- **Google Colab or local setup with GPU support**

### Install Required Libraries
To install the necessary libraries, use the following pip command:

```bash
pip install torch transformers diffusers datasets matplotlib

