# Pneumonia Classification Model

This repository contains a Jupyter Notebook (`.ipynb` file) for a pneumonia classification model developed using Convolutional Neural Networks (CNN) and transfer learning techniques. The model aims to classify chest X-ray images to detect the presence of pneumonia.


## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Training](#ModelTraining)
- [Results](#Results)

## Introduction

Pneumonia, a deadly respiratory infection claiming the lives of over 2,000 individuals annually, is a severe disease that ranks among Australia's top 20 causes of death. My goal is to implement a machine-learning model that can diagnose pneumonia in the early stages using chest images of existing pneumonia patients and normal patients. This model could lead to an increase in the probability that medical professionals will be able to diagnose pneumonia cases in patients early and the accuracy of pneumonia diagnosis.

## Dataset

The dataset used for training and testing the model is publicly available and consists of labeled chest X-ray images. The images are categorised into two classes: Pneumonia and Normal. You can see the dataset from [Kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia).

## ModelTraining

The notebook includes detailed steps for preprocessing the data, defining the model architectures, and training the models. Two models are trained:

1. A custom Convolutional Neural Network (CNN)
2. A transfer learning model using Inception V3
Both models are implemented using TensorFlow.

## Results

The models achieve the following performance metrics on the test dataset:

### Custom CNN Model
- Accuracy: 75%
- Precision: 
  - NORMAL: 0.96%
  - PNEUMONIA: 0.72%
- Recall:
  - NORMAL: 0.36%
  - PNEUMONIA: 0.99%
- F1 Score:
  - NORMAL: 0.53%
  - PNEUMONIA: 0.83%

### Inception V3 Model
- Accuracy: 81%
- Precision: 
  - NORMAL: 0.95%
  - PNEUMONIA: 0.77%
- Recall:
  - NORMAL: 0.52%
  - PNEUMONIA: 0.98%
- F1 Score:
  - NORMAL: 0.67%
  - PNEUMONIA: 0.86%

