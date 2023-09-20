# Cats and Dogs Classifier using Convolutional Neural Networks

## Overview

This project implements a deep-learning model to classify images of cats and dogs. It uses Convolutional Neural Networks (CNNs) to extract meaningful features from the images. Additionally, it employs image generators and augmentation techniques to prevent overfitting and improve the model's generalization on unseen data.

### Dataset

The training data for this project was obtained from the Kaggle competition [Dogs vs. Cats](https://www.kaggle.com/c/dogs-vs-cats). This dataset consists of thousands of images of cats and dogs, which were used for training and evaluation.

## Getting Started

### Prerequisites

Make sure you have the following prerequisites installed:

- Python 3.x
- TensorFlow (or other deep learning framework)
- Jupyter Notebook (optional but recommended)
- Pandas, Matplotlib, and other necessary libraries

### Usage

**Data Preparation**: Download the dataset from [Kaggle](https://www.kaggle.com/c/dogs-vs-cats) and organize it into a suitable directory structure. You can use the following structure:

   ```
   ├── dataset
   │   ├── train
   │   │   ├── cat
   │   │   └── dog
   │   └── test
   │       └── unknown
   ```

