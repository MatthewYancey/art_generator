# Art Generator

## Overview
This repo was to explore using a progressive GANs model to generate art.

This work barrows heavily from the Pytorch DCGAN Tutorial (https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html) and the NVIDA paper on progressive GANs (https://research.nvidia.com/publication/2017-10_Progressive-Growing-of)

## Notebooks
**model_progressive_gans_anime.ipynb**: This notebook tests the GANs network on a known dataset of anime characters to see if it will generate favorable results. 

**model_progressive_gans_art_001.ipynb**: Image size of 32 pixels.
* No link
* No output
* No results


**model_progressive_gans_art_002.ipynb**: Image size of 64 pixels trained from the lower resolution model. Results: Good with some signs of mode-collapse.

**model_progressive_gans_art_003.ipynb**: Image size of 64 pixels trained from scratch.
Results: Good output with less mode-collapse than the progressive GANs on the 32 model.

**model_progressive_gans_art_004.ipynb**: Image size of 128 pixels trained from scratch. Results are highly pixelated and there is a high degree of mode-collapse.

**model_progressive_gans_art_005.ipynb**: Image size of 128 pixels trained from the lower resolution model. Results look fair with no sign of mode-collapse.

**model_progressive_gans_art_006.ipynb**: Needs to be run.


## Backlog
* Run 001 and 006
* Things to try
    1. test with number of channels equal to the number of layers
    3. try the tips from (https://github.com/soumith/ganhacks)
        * batch norm, leaky relu.
* good resource (https://medium.com/@jonathan_hui/gan-why-it-is-so-hard-to-train-generative-advisory-networks-819a86b3750b)



