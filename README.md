# Credit Card Fraud Detection

This project aims to detect fraudulent credit card transactions using machine learning. The dataset used is highly imbalanced, with the majority of transactions being legitimate. The primary algorithm used is Logistic Regression, which helps in predicting whether a transaction is fraudulent or not.

## Table of Contents
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Dataset
The dataset used for this project is creditcard.csv, which contains 284,807 transactions with 30 feature columns including the transaction Time and Amount, and the Class column indicating whether a transaction is fraudulent (1) or legitimate (0).

## Dependencies
- Python 3.x
- Numpy
- Pandas
- Scikit-learn

## Usage

Ensure you have the dataset file creditcard.csv in the project directory.

Run the script to train and evaluate the model:

bash
python fraud_detection.py

The script will:

- Load and preprocess the dataset.
-  Balance the dataset using under-sampling.
-  Split the dataset into training and testing sets.
-  Train a Logistic Regression model.
-  Evaluate the model on both training and testing sets.
## Expected Results
The script will output the following results:

- Training Data Accuracy: The accuracy of the model on the training set.
- Test Data Accuracy: The accuracy of the model on the testing set.
- Training data accuracy: 0.94
- Test data accuracy: 0.92
 ##  Dataset
The dataset used in this project is available on Google Drive. You can download it using the following link:

https://drive.google.com/file/d/1rRogMGc0D9QqR9Zhszw54tBpsFG4gcNR/view?usp=sharing
