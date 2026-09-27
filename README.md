# PCD Assignment 02 - Image Enhancement

This repository contains our second Digital Image Processing assignment about image enhancement.

We test several enhancement methods on dark, bright, low-contrast, and blurred images. The main enhancement algorithms are implemented manually, while `scikit-image` is used for test images, controlled degradation, and evaluation metrics.

## Methods

The methods implemented in the notebook are:

- Log Transformation
- Gamma Correction
- Contrast Stretching
- Histogram Equalization
- Laplacian Sharpening
- Unsharp Masking
- 2D Convolution

Each image is tested at five increasing degradation levels so we can see how the methods behave as the image quality becomes worse.

## Images

We use three grayscale images from `skimage.data`:

- Camera
- Coins
- Moon

The images have different characteristics such as edges, texture, smooth regions, and different intensity distributions.

## Evaluation

The results are compared visually and using:

- Mean Squared Error (MSE)
- Peak Signal-to-Noise Ratio (PSNR)
- Structural Similarity Index (SSIM)

The comparison is performed against the original reference image.

## Repository Structure

```text
.
├── PCD_Assignment02.ipynb
└── report/
    └── PCD_Assignment02.pdf
```

The notebook contains the full implementation, experiments, plots, and evaluation results.