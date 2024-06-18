# Credit Card Fraud Detection Using Machine Learning

# Overview
This project aims to detect fraudulent credit card transactions using machine learning algorithms. By comparing multiple algorithms, we identify the most effective model for this task, which is the Random Forest algorithm.

# Table of Contents 
  Introduction
  Dataset
  Algorithms Used
  Evaluation Metrics
  Results
  Installation

# Introduction
Credit card fraud is a significant concern in the financial industry, with substantial losses each year. This project leverages machine learning to enhance fraud detection capabilities. By experimenting with various algorithms, we can determine the most suitable model for accurately identifying fraudulent transactions.

# Dataset
The dataset used in this project is the Credit Card Fraud Detection dataset from Kaggle. It contains transactions made by European cardholders in September 2013. The dataset is highly imbalanced, with only 492 frauds out of 284,807 transactions.

#Algorithms Used
We implemented and evaluated the following machine learning algorithms:

  Logistic Regression
  Decision Tree
  Support Vector Machine (SVM)
  k-Nearest Neighbors (k-NN)
  Random Forest
  Gradient Boosting

# Evaluation Metrics
To evaluate the performance of each algorithm, we used the following metrics:

  Accuracy
  Precision
  Recall
  F1 Score
  Area Under the Receiver Operating Characteristic Curve (AUC-ROC)

# Results
After comparing the performance of various algorithms, the Random Forest algorithm was found to be the most effective for this task, achieving the best balance between precision and recall. Below is a summary of the performance metrics for the Random Forest algorithm:

  Accuracy: 99.94%
  Precision: 90.78%
  Recall: 86.50%
  F1 Score: 88.60%
  AUC-ROC: 98.97%

# Installation
To run this project locally, follow these steps:

# Clone the repository:
git clone https://github.com/saurabh2129/Creditcard-fraud-detection-using-machine-learning

# Navigate to the project directory:
cd Creditcard-fraud-detection-using-machine-learning

