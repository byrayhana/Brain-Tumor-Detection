# Brain Tumor Classification using Convolutional Neural Networks (CNN)



## Introduction

This repository contains Python code for a Convolutional Neural Network (CNN) based model to classify brain tumor images into four categories: glioma tumor, meningioma tumor, no tumor, and pituitary tumor.

## Table of Contents
- [Introduction](#introduction)
- [Dependencies](#dependencies)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Model Architecture](#model-architecture)
- [Training](#training)

## Dependencies

The code is written in Python and utilizes the following libraries:

- numpy
- pandas
- keras
- scikit-learn
- cv2 (OpenCV)
- tensorflow
- tqdm

Ensure you have these libraries installed before running the code.

## Dataset

The dataset used for training and testing consists of brain tumor images categorized into four classes: glioma tumor, meningioma tumor, no tumor, and pituitary tumor. 
[Dataset](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri)

## Data Preprocessing

The code performs the following data preprocessing steps:

1. Load and resize images to a consistent size (150x150 pixels).
2. Shuffle the data.
3. Split the data into training and testing sets.
4. Convert labels into categorical format.

## Model Architecture

The CNN model architecture consists of several layers:

1. Convolutional layers with various filter sizes and activation functions (ReLU).
2. MaxPooling layers to downsample the spatial dimensions.
3. Dropout layers to prevent overfitting.
4. Fully connected (Dense) layers with ReLU activation functions.
5. Output layer with softmax activation for multi-class classification.

The model is compiled with the Adam optimizer and categorical cross-entropy loss function.

## Training

The model is trained for 20 epochs using the training data. The training progress is tracked, and validation data is used to assess model performance during training.

Please note that this README provides an overview of the code and its functionality. For more detailed explanations and comments, refer to the actual code file.

For any questions or inquiries, feel free to reach out!
