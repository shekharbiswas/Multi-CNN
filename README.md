# **Age and Gender Prediction using CNN**

## **Overview**

This repository contains code for constructing and training Convolutional Neural Network (CNN) models to predict the age and gender of people based on their face images. We will be developing two distinct models:

1. Custom CNN Model: A model designed and trained from scratch.
2. Fine-Tuned Pre-trained Model: A pre-trained architecture fine-tuned for the specific task of age and gender prediction.

## **Dataset**
The dataset consists of 5,000 labeled face images, each of size 128x128 pixels. The face images are taken from the UTKFace dataset. These images will be used to train our models and later to predict the ages and genders of unseen test data.

## **Objectives**
The main objectives of this project are:

- To construct and train a custom CNN model for age and gender prediction.
- To fine-tune a pre-trained model for the same.
- To efficiently utilize the GPU resources, given the constraints on time and computational power.

## **Evaluation Metrics**
The performance of the models will be evaluated based on two tasks:

- Age Estimation: Evaluated using the Mean Absolute Error (MAE).
- Gender Classification: Evaluated using the accuracy of the predicted labels.
