# MOG
Explores fitting parametric models MOG to visual data, and perform inference with the model.

## Requirment
Tested against Python 3.6.6. Required Python modules:
* numpy
* scipy
* matplotlib
* pillow

------
## Introduction
### Part I
The aim of part A is to fit one Gaussian model to the data for skin and another Gaussian to non-skin pixels, and use this to find the posterior probability that each pixel in an image is skin.\
\
The aim of part B is to fit a mixture of Gaussians model to one dimensional data.\
\
The aim of part C is to fit a mixture of Gaussians model to the RGB data.\
### Part II
Train a mixture of Gaussians model and use it to inferece apples in unknown image.
