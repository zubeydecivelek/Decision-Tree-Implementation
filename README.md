# Flower Species Classification using Decision Trees

## Introduction
This machine learning project focuses on implementing a decision tree model for classifying flower species using the ID3 algorithm. The Flower Species Dataset, consisting of 10 different flower species, is utilized for training and testing. The project involves preprocessing the data, implementing the ID3 algorithm for decision tree construction, and evaluating the model's performance.

## About Data
The dataset includes train and test images, with each species dataset having 600 training images, 50 validation images, and 50 testing images. The goal is to develop a decision tree model capable of accurately classifying flower species based on visual features extracted from the images.

**Dataset Link:**
[Flower Species Dataset](https://drive.google.com/file/d/18m0MSatxOOPM7FkpbvVun20w7RWeNI_X/view)

## Preprocessing
- Displayed a sample image from the dataset to showcase the visual nature of the flower species data.
- Resized the image to 64x64 pixels for efficient training.
- Applied edge detection using the Canny algorithm to extract important shape features.

## Flower Species Classification (ID3 Algorithm)
This section focuses on the primary goal of flower species classification using the ID3 decision tree technique. Key steps include:
- Extracting class names and visualizing class distribution in the training set using a pie chart.
- Loading and processing images for training, testing, and validation sets.
- Creating a bar chart to visualize the distribution of samples across different flower species in the dataset.

## ID3 Algorithm
The ID3 algorithm is employed for classification, utilizing features such as entropy and information gain to construct an effective decision tree. The algorithm aims to discover patterns and relationships in the data, contributing to accurate flower species classification.

## Feature Importance
An analysis of feature importance is conducted to identify the key factors influencing model predictions. The top features are visualized using a bar chart, providing insights into the significance of different features in the decision-making process.

## Model Evaluation
The decision tree model is evaluated using different hyperparameter values, considering various depths. The best-performing model is selected based on accuracy, precision, recall, and F1 score. Decision tree rules for the best model are presented for transparency.

## Testing on Test Dataset
The selected model is tested on the test dataset to assess its generalization capabilities. The accuracy, precision, recall, and F1 score on the test set are reported. A confusion matrix heatmap provides a visual representation of the model's performance on different flower species.

## Pruning Decision Tree
Post-pruning analysis is conducted to optimize the decision tree's performance on unseen data. The pruning process involves identifying and removing twigs from the decision tree. The final pruned decision tree is evaluated on the test set, and the results are compared with the pre-pruned model.
