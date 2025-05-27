# EE413 Image Compression and Classification Project

## Overview

This project applies **image compression** and **classification** techniques using **wavelet transforms** and **compressed sensing** to the **Mini-ImageNet** dataset. We use **deep learning models** (ResNet18) to classify images and evaluate how compression affects classification performance.

The project demonstrates:
- Wavelet compression at different ratios.
- Fine-tuning pre-trained models to handle compressed data.
- Compressed sensing and model evaluation.

## How to Use

1. Open the [Google Colab notebook](https://colab.research.google.com/) from this repository.
2. Run the cells in order to:
   - Train the model.
   - Perform wavelet compression and evaluate its impact.
   - Perform compressed sensing and evaluate model robustness.
3. Ensure the **Mini-ImageNet dataset** is loaded into the notebook or use the provided data link.

## Dataset

The dataset used in this project is **Mini-ImageNet**, a subset of ImageNet containing 100 classes with 600 images each.

- **Dataset Link**: Since the dataset is large, it is hosted on **Google Drive**. You can download it using the link below:
  - [Download Mini-ImageNet Dataset](https://drive.google.com/file/d/your-link-here)

## Dependencies

Make sure to install the necessary Python libraries to run the project. Here are the required dependencies:

- `torch`
- `torchvision`
- `pywt` (PyWavelets for wavelet transforms)
- `cvxpy` (for compressed sensing)
- `scikit-learn`
- `matplotlib`
- `numpy`

Install the dependencies using:

```bash
pip install -r requirements.txt
