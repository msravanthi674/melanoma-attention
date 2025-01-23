# Melanoma Classification Project
## Overview
This project implements a binary classification model to predict skin lesion characteristics using patient image data. It leverages a pre-trained ResNet18 model for feature extraction and fine-tunes it for the classification task.
## Steps
### 1. **Setup and Imports**
- Imported necessary libraries: PyTorch, torchvision, OpenCV, Pandas, and more.
- Configured device support (CPU/GPU).
- Defined a utility function to seed randomness for reproducibility.
### 2. **Dataset Loading**
- Loaded and previewed the dataset using Pandas.
- Duplicated the dataset for testing purposes.
### 3. **Custom Dataset Class**
- Created a `CustomDataset` class for loading images and targets.
- Preprocessed images using resizing, normalization, and tensor conversion.
### 4. **Model Definition**
- Loaded a pre-trained ResNet18 model.
- Modified the fully connected layer to handle binary classification.
### 5. **Inference**
- Implemented a dummy inference loop to generate predictions on test data.
- Predictions were saved as a CSV file for further analysis.
