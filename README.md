# Machine-Learning-Driven-Calibration-of-Traffic-Models-with-Video-Data

## Overview
This repository contains a collection of satellite image datasets in JPEG and PNG formats, which have been compressed using a specific image compression algorithm (https://doi.org/10.20944/preprints202404.1918.v1). The data are divided into three sets: training, validation, and test. The training set includes the original images as well as the compressed and decompressed versions.

## Dataset Organization
The dataset structure is as follows:

dataset-of-satellite-images/
│
├──README.md
├──dataset_jpeg.zip
├──── train/
│ 	├── original/
│ 	├── compressed/
│ 	└── recovered/
├──── val/
│
├──── test/
│
├──dataset_png.zip
├──── train/
│ 	├── original/
│ 	├── compressed/
│ 	└── recovered/
├──── val/
│
└──── test/

- **train/**: Contains original, compressed, and recovered images.
- **val/** and **test/**: Contain only original images.

## Usage

To use this dataset, clone the repository using the following command with Git LFS enabled:
git lfs clone https://github.com/Ekaterina-Lopukhova/Machine-Learning-Driven-Calibration-of-Traffic-Models-with-Video-Data/dataset-of-satellite-images.zip
