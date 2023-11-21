# Chinese Glyphs VAE Exploration

## Overview
This project learns the latent space of all Chinese unicode glyphs using a Variational Autoencoder (VAE). The latent space is explored through t-SNE and latent space interpolation videos.

Datasets with 64x64 and 128x128 images have been tested.

## Instructions
glyph_explorer_dataset_generator.ipynb - Generates the dataset of 64x64 or 128x128 images of all Chinese unicode glyphs. The dataset is a folder of .png files titled with the unicode value of the glyph.

glyph_explorer_vae.ipynb (and _128 variant) - Defines and trains a VAE on the dataset of images.

glyph_explorer_interpolater.ipynb (and _128 variant) - Performs a latent space interpolation between any sequence of glyphs and generates a video of the interpolation.

<video width="512" height="512" controls>
  <source src="interpolations/interpolation_128_2.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
