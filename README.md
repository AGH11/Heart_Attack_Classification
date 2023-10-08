# Machine Learning for Heart Disease Prediction

This repository contains Python code for a machine learning project focused on predicting heart disease using the "heart.csv" dataset. The code is organized as follows:

## Data Loading and Exploration
- The dataset is loaded using the Pandas library.
- Initial exploration of the dataset, including data types and summary statistics.

## Data Preprocessing
- Conversion of the 'oldpeak' column to the 'int64' data type.
- Selection of relevant features for model training.

## Train-Test Split
- Division of the dataset into training and testing sets using the train_test_split function from scikit-learn.

## Logistic Regression Model
- Training a logistic regression model on the training set.
- Prediction on the test set and evaluation using Jaccard score, log loss, and a classification report.
- Visualization of the confusion matrix.

## Decision Tree Classifier
- Training a decision tree classifier on the training set.
- Prediction on the test set and evaluation using Jaccard score, log loss, and a classification report.
- Visualization of the confusion matrix.

## Support Vector Machine (SVM) Classifier
- Training a linear SVM classifier on the training set.
- Prediction on the test set and evaluation using Jaccard score, log loss, and a classification report.
- Visualization of the confusion matrix.

Note: Each model's performance metrics and confusion matrix are displayed for comprehensive evaluation.

Feel free to explore and modify the code for further experimentation and improvement.
