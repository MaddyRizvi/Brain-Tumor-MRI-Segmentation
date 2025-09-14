# Brain Tumor Auto-Segmentation (MRI)

Brain tumor auto-segmentation using Magnetic Resonance Imaging (MRI). This project demonstrates data preprocessing, 3D sub-volume extraction, MRI standardization, and deep learning–based segmentation with Dice coefficient and soft Dice loss. Includes evaluation metrics (sensitivity, specificity) for tumor detection performance.

Topics / Tags:
python · deep-learning · tensorflow · keras · medical-imaging · mri · brain-tumor · segmentation · computer-vision · healthcare-ai

# Brain Tumor MRI Segmentation

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg?logo=python)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg?logo=tensorflow)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-red.svg?logo=keras)](https://keras.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Stars](https://img.shields.io/github/stars/MaddyRizvi/Brain-Tumor-MRI-Segmentation?style=social)](https://github.com/Brain-Tumor-MRI-Segmentation/stargazers)
[![Forks](https://img.shields.io/github/forks/MaddyRizvi/Brain-Tumor-MRI-Segmentation?style=social)](https://Brain-Tumor-MRI-Segmentation/network/members)

> Deep learning pipeline for brain tumor auto-segmentation using MRI scans — includes preprocessing, Dice loss, and evaluation metrics.


## Overview
The project demonstrates how to:
- Preprocess MRI scans
- Extract 3D sub-volumes from brain scans
- Standardize MRI image data
- Implement dice coefficient and soft dice loss for segmentation evaluation
- Train a neural network for brain tumor segmentation
- Compute sensitivity and specificity metrics for performance evaluation

## File Structure
- **Brain_Tumor_Segmentation.py**: Main Python assignment file with completed functions for sub-volume extraction, standardization, dice coefficient, loss function, and evaluation metrics.
- **README.md**: This file with information about the repository.

## Key Implemented Functions
- `get_sub_volume`: Extracts sub-volumes from MRI scans for training.
- `standardize`: Normalizes each channel and z-slice of MRI images.
- `single_class_dice_coefficient`: Dice metric for a single class.
- `dice_coefficient`: Mean dice coefficient across classes.
- `soft_dice_loss`: Loss function for segmentation tasks.
- `compute_class_sens_spec`: Sensitivity and specificity computation for segmentation results.

## Usage
Run the Python file in Jupyter Notebook or Python environment to preprocess MRI data and evaluate segmentation models.

## Acknowledgments
This project is inspired by deep learning applications in medical imaging, particularly brain tumor segmentation tasks in MRI data.
