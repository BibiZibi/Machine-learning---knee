# Knee Image Super-Resolution using Multi-View Learning
## Description

The goal of this project was to develop a machine learning model capable of generating a high-quality knee image based on multiple low-quality inputs.

The model takes:

- 6 low-resolution images of the knee (different views)
- and reconstructs 1 high-resolution image

The entire training process is based on preprocessed datasets stored in:

- `lowresolution.npy` – containing low-quality multi-view inputs
- `highresolution.npy` – containing corresponding high-quality target images

This approach leverages multi-view information to improve reconstruction quality compared to single-image super-resolution methods.

## Problem Statement

Medical imaging often suffers from limited resolution due to hardware constraints or noise. Enhancing image quality is crucial for:

- better diagnosis
- improved visualization of anatomical structures
- reduced need for repeated scans

This project focuses on reconstructing a high-resolution knee image from multiple low-resolution projections.
