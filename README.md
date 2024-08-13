## (Bank Marketing Prediction)
This project uses a decision tree classifier to predict whether a client will subscribe to a term deposit based on the UCI Bank Marketing dataset.

Overview

Data Source: UCI Bank Marketing Dataset
Data Preprocessing:
Categorical variables are encoded using one-hot encoding.
The target variable 'y' is converted from 'yes'/'no' to binary (1/0).
Steps

Data Loading: Load the dataset directly from the UCI repository.
Encoding: Apply one-hot encoding to categorical variables.
Feature and Target Split: Separate the data into features (X) and target (y).
Train-Test Split: Split the data into training and testing sets (80% train, 20% test).
Model Training: Train a decision tree classifier on the training data.
Prediction: Make predictions on the testing data.
Evaluation:
Calculate accuracy of the model.
Generate a classification report with precision, recall, and F1-score.
Visualization: Plot the decision tree to visualize the model's decision-making process.
Results

Accuracy: The accuracy of the decision tree classifier on the test data.
Classification Report: Detailed performance metrics including precision, recall, and F1-score.
Requirements

pandas for data manipulation.
scikit-learn for machine learning and model evaluation.
matplotlib for plotting the decision tree.
Usage

Run the script to load the data, preprocess it, train the model, and evaluate its performance.
Visualize the decision tree to understand the model's decisions.
