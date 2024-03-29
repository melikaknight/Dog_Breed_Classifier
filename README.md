# Dog Vision

## Project Overview

Dog Vision is a deep learning project aimed at classifying different breeds of dogs using convolutional neural networks (CNNs). The project utilizes the TensorFlow and Keras libraries to build and train the model on a dataset of dog images.

## Features

- Image preprocessing and augmentation for robust model training.
- CNN model architecture with multiple layers for feature extraction and classification.
- Evaluation of model performance on a separate test dataset.
- User-friendly interface for uploading and classifying new dog images.
## Dataset
The dataset consists of over 10,000 labeled training images and 10,000 unlabeled test images, covering 120 different breeds of dogs. The model's performance is evaluated based on its ability to predict the probabilities of each dog breed for the test images, as specified in Kaggle's dog breed identification competition.

## Installation

To run this project, you will need to have Python installed on your system. Clone this repository and install the required dependencies:

```bash
git clone https://github.com/your-username/dog_vision.git
cd dog_vision
pip install -r requirements.txt
