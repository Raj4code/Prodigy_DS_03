# Prodigy_DS_03
This repository contains the implementation of a Decision Tree Classifier for classification tasks. 
A Decision Tree is a popular and powerful tool in machine learning used for both classification and regression problems. 

Features:
Easy to Understand and Interpret: Decision Trees are intuitive and easy to visualize,
making them an excellent choice for understanding the structure of the data and the importance of different features.

Handles Both Numerical and Categorical Data: This implementation can handle datasets with both types of features.
Built-in Support for Pruning: To avoid overfitting, the classifier supports techniques such as max depth restriction and minimum samples per leaf.
Feature Importance: Provides insights into which features are most important in making predictions.


Usage:

Training the Model
Data Preparation: Prepare your dataset in a CSV format. Ensure that the dataset contains both features and the target variable.
Training the Model: Use the provided script to train the model on your dataset.
python train_model.py --data_path path_to_your_dataset.csv

Evaluating the Model
Evaluate the performance of the trained model using various metrics such as accuracy, precision, recall, and F1-score.
python evaluate_model.py --data_path path_to_your_dataset.csv
