# U-Net for Car Segmentation

This project implements the U-Net architecture based on the paper  
"U-Net: Convolutional Networks for Biomedical Image Segmentation" (Ronneberger et al., 2015).  
The model is applied to the Carvana Image Masking Challenge dataset to perform pixel-wise car segmentation.

## Features

- Encoder–decoder CNN with skip connections for preserving spatial information
- Trained using binary cross-entropy loss
- Data augmentation for improved generalization

## Dataset

The dataset used in this project is from the Carvana Image Masking Challenge.  
You can download it from Kaggle:

[Carvana Image Masking Challenge - Kaggle](https://www.kaggle.com/competitions/carvana-image-masking-challenge/data)

## References

- Olaf Ronneberger, Philipp Fischer, Thomas Brox.  
  *U-Net: Convolutional Networks for Biomedical Image Segmentation*.  
  In *Medical Image Computing and Computer-Assisted Intervention (MICCAI)*, 2015.  
  [Paper on arXiv](https://arxiv.org/abs/1505.04597)
