# Art Generator

## Overview
This repo was to explore using a progressive GANs model to generate art.

This work barrows heavily from the Pytorch DCGAN Tutorial (https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html) and the NVIDA paper on progressive GANs (https://research.nvidia.com/publication/2017-10_Progressive-Growing-of)

## Notebooks
**model_progressive_gans_anime.ipynb**: This notebook tests the GANs network on a known dataset of anime characters to see if it will generate favorable results. 

**model_progressive_gans_art_001.ipynb**: Image size 32 pixels.
* No link
* No output
* No results


**model_progressive_gans_art_002.ipynb**: Image size 64. Results: Good with some signs of mode-collapse.

**model_progressive_gans_art_001.ipynb**:

**model_progressive_gans_art_001.ipynb**:

**model_progressive_gans_art_001.ipynb**:

**model_progressive_gans_art_001.ipynb**:

**model_progressive_gans_art_001.ipynb**:

## Backlog
* Things to try
    1. test with number of channels equal to the number of layers
    2. try it with the anime face dataset (https://github.com/jayleicn/animeGAN)
    3. try the tips from (https://github.com/soumith/ganhacks)
        * batch norm, leaky relu.
    4. post question to Machine Learning Subreddit or other site?
* Clean this repo.
* fix the images saved to tensorboard. They probably just need to be scaled.



