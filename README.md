# Wine Quality Prediction Using K-Nearest Neighbors (KNN) Classifier

This project demonstrates the implementation of the K-Nearest Neighbors (KNN) algorithm to predict wine quality based on various physicochemical properties using the Wine Quality dataset.

## Overview

The notebook covers the following steps:
- Reading and preprocessing the Wine Quality dataset.
- Splitting the data into training and testing sets.
- Standardizing the features using `StandardScaler`.
- Training a KNN model with default parameters.
- Evaluating model performance using accuracy, confusion matrix, and classification report.
- Hyperparameter tuning using GridSearchCV to find the best number of neighbors for KNN.
- Visualizing the confusion matrix of the best model.

## Requirements

- Python 3.x
- Pandas
- Scikit-learn
- Seaborn
- Matplotlib

## How to Run

1. Install the required libraries using:
   ```bash
   pip install pandas scikit-learn seaborn matplotlib
