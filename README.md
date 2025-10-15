# Plant Disease Classification using Transfer Learning

This project uses a deep learning model to classify plant diseases from images. It uses transfer learning with the MobileNetV2 architecture in TensorFlow/Keras.

## Features
-   Model built using TensorFlow and Keras.
-   Uses the MobileNetV2 model pre-trained on ImageNet.
-   Employs a two-phase fine-tuning strategy for high accuracy.
-   Optimized for fast training in Google Colab.

## Setup and Installation

To run this project, you need to set up the dataset and the notebook environment.

**1. Dataset**
-   Download the dataset from Kaggle:
    https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf

**2. Google Colab Environment**
-   Open the `tomato_disease.ipynb` notebook in Google Colab.
-   Upload the `New Plant Diseases Dataset(Augmented).zip` file to the root of your Google Drive.
-   The notebook is configured to mount your Google Drive, copy the zip file to the local runtime for fast access, and then start training.
