# Application of PCA for Color Images

This repository is for DA623: Computing with Signals course project. It contains code demonstrating the application of Principal Component Analysis (PCA) for compressing and analyzing colored images.

## Overview

In this project, we look at how PCA can be used to compress colored images. We do this by applying PCA to each of the channels of an image – red green and blue – independently in order to reduce complexity. Next, the compressed channels are joined together so as to recreate the final compressed RGB (Red Green Blue) representation.

## Key Steps

1. **Understanding PCA**: We delve into the fundamentals of PCA, starting from calculating them all and transforming and reconstructing data.

2. **Image Quantization**: We examine image quantization which is an important part of image compression where it reduces number of different colours that can be used while keeping visual quality good enough.

3. **PCA Implementation**: From scratch, we implement PCA, giving explanations for each step involved.

4. **Dimensionality Reduction**: We explore the process of dimensionality reduction using PCA and determine an optimal number of principal components for compression.

5. **Reconstruction**: We inverse-transform the compressed data to reconstruct the original image, allowing us to visualize the impact of compression on image quality.


## Contents

- `tutorial_notebook.ipynb`: Contains Jupyter notebook demonstrating the application of PCA for colored images.
- `images/`: This directory contains sample colored images used for explanation.
- `README.md`: You are reading it right now! This file provides an overview of the repository and its contents.

## Usage
To run the tutorial, clone the repository and run the notebook.

## Dependencies
- Jupyter Notebook
- Python
- cv2
- Matplotlib
- NumPy
- scikit-learn
- ipywidgets

## References
- [A Step-by-Step Explanation of Principal Component Analysis (PCA)](https://builtin.com/data-science/step-step-explanation-principal-component-analysis)
- [Image Compression Using Principal Component Analysis (PCA)](https://www.enjoyalgorithms.com/blog/image-compression-using-pca)
- [A quick guide to color image compression using PCA in python](https://towardsdatascience.com/dimensionality-reduction-of-a-color-photo-splitting-into-rgb-channels-using-pca-algorithm-in-python-ba01580a1118)
- [RGB Color Image Compression Using Principal Component Analysis](https://towardsdatascience.com/rgb-color-image-compression-using-principal-component-analysis-fce3f48dfdd0)
