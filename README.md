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
[practicalMixGaussA.ipynb](https://github.com/alstondu/MOG/blob/main/Part_I/practicalMixGaussA.ipynb) fits one Gaussian model to the data for skin and another Gaussian to non-skin pixels, and use this to find the posterior probability that each pixel in an image is skin.\
\
[practicalMixGaussB.ipynb](https://github.com/alstondu/MOG/blob/main/Part_I/practicalMixGaussB.ipynb) fits a mixture of Gaussians model to one dimensional data.\
\
[practicalMixGaussC.ipynb](https://github.com/alstondu/MOG/blob/main/Part_I/practicalMixGaussC.ipynb) fits a mixture of Gaussians model to the RGB data.\
### Part II
[practicalMixGauss_Apples.ipynb](https://github.com/alstondu/MOG/blob/main/Part_II/practicalMixGauss_Apples.ipynb) trains a mixture of Gaussians model and use it to inferece apples in unknown image.
