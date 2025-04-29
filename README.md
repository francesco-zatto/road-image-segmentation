# Road Image Segmentation

This project implements a deep learning approach to segment roads from satellite images using a U-Net architecture. It includes dataset download, preprocessing, model training, evaluation, and testing.

## Dataset

- **Source:** [Kaggle - Satellite Images for Road Segmentation](https://www.kaggle.com/datasets/sanadalali/satellite-images-for-road-segmentation)
- Includes satellite images and ground truth masks for training and testing.

## Installation

```bash
pip install tensorflow keras opencv-python matplotlib numpy scikit-learn kagglehub

Download the Dataset

import kagglehub
path = kagglehub.dataset_download("sanadalali/satellite-images-for-road-segmentation")

Alternatively, you can download and place it manually in the project directory.

Features

U-Net implementation from scratch using Keras

Combined Binary Cross-Entropy and Dice Loss

Visualization of predictions vs. ground truth

IoU-based threshold optimization

Optional training on augmented/generated images

TODO

Add image/mask rotation as data augmentation

Test with alternative datasets

Add a 4th channel with Gaussian probability maps

Ensure consistent RGB channel ordering


License

This project is open-source under the MIT License.

