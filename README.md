# NEURAL_STYLE_TRANSFER

This repository implements a Neural Style Transfer (NST) technique, inspired by the [TensorFlow NST blog post](https://colab.research.google.com/github/tensorflow/models/blob/master/research/nst_blogpost/4_Neural_Style_Transfer_with_Eager_Execution.ipynb#scrollTo=dzJTObpsO3TZ). The goal of this project is to transform a personal image into an artistic avatar by applying a specific style using deep learning.

## Features

- **Neural Style Transfer (NST):** Transforms your image (avatar) into a stylized version based on a reference artwork.
- **Customization:** Allows users to choose a custom image (e.g., a photo) and style reference (e.g., painting, artwork, etc.).
- **Fixes & Improvements:** The original code has been modified and optimized to improve performance and results when generating avatars based on a chosen style.

## Try it on Google Colab

You can quickly run the style transfer process in a Google Colab environment by clicking the button below:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HaizeaRL/NEURAL_STYLE_TRANSFER/Neural_Style_Transfer_with_Eager_Execution.ipynb)

Once opened in Colab, you can upload your avatar and style images and execute the code with a simple click to create your stylized avatar!


## Notes

- The model uses TensorFlow's eager execution to apply the style to the avatar.
- Experiment with different style images to create unique avatars.

