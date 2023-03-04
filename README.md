# 🐶 End-to-end multiclass Dog Breed Classification

This notebook builds an end-to-end multiclass image classifier using TensorFlow 2.0 and TensorFlow hub.

## 1. Problem

Identifying the breed of dog given an image of a dog

## 2. Data

The data we are going to use is from Kaggle's dog breed identification competition.

https://www.kaggle.com/competitions/dog-breed-identification/data

## 3. Evaluation

The evaluation is a file with the prediction probabilities for each dog breed of each test image.

https://www.kaggle.com/competitions/dog-breed-identification/overview/evaluation

## 4. Features

Some information about the data

- We are dealing with images (unstructured data) so it is probably best to use deep/transfer learning.
- There are 120 breeds of dogs (this means there are 120 different classes)
- There are about ~10,000 images in training set (images with labels)
- There are about ~10,000 images in testing dataset (images without labels)

> Prediction files can be found here (these files are > 25mb in size): https://www.mediafire.com/folder/zu9i2g50rdyvl/predictions
