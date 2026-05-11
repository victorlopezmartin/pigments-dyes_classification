# Selection of Key Spectral Bands for the Identification of Historical Dyes and Pigments Using Hyperspectral Fluorescence Imaging

This repository contains part of the work developed for the Bachelor's Thesis of the Physics Degree at the University of Granada.

The repository only includes the Jupyter notebooks related to the classification and recognition of dyes and pigments using different machine learning approaches and classification strategies.

The notebooks cover:
- Direct multiclass classification
- Hierarchical classification models
- PCA-based dimensionality reduction
- Spectral band selection methods
- Simulation of multispectral systems

> [!NOTE]
> The objective is to evaluate different methodologies for the identification of historical pigments and dyes from hyperspectral fluorescence imaging data.

***

## Dataset

The dataset used in this work was provided by the Color Imaging Lab, a research group from the University of Granada focused on spectral and hyperspectral image analysis applied to cultural heritage and material identification.

The group has also developed software tools for hyperspectral and reflectance image analysis. More information can be found in their repository:

https://github.com/colorimgugr/HyperDocApp

The original hyperspectral data are stored as hyperspectral cubes (hypercubes), where each pixel contains spectral information along multiple wavelength bands. Therefore, the data require preprocessing and reshaping operations before applying machine learning models.

In this repository, the processed dataset is already included, so the notebooks directly work with the transformed data matrices used for classification experiments.
