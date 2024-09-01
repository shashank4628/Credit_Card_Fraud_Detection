# Credit Card Fraud Detection

This project focuses on identifying fraudulent credit card transactions using machine learning techniques. The dataset employed is significantly imbalanced, with most transactions being legitimate. Logistic Regression is the primary algorithm used to predict whether a transaction is fraudulent.

## Table of Contents
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Dataset
The dataset for this project is `creditcard.csv`, which includes 284,807 transactions across 30 feature columns, such as transaction time, amount, and a `Class` column indicating whether a transaction is fraudulent (1) or legitimate (0).

## Dependencies
- Python 3.x
- Numpy
- Pandas
- Scikit-learn

## Usage
Ensure the `creditcard.csv` file is located in the project directory.

Run the script to train and evaluate the model:

```bash
python fraud_detection.py
The script will perform the following steps:

1. Load and preprocess the dataset.
2. Balance the dataset through under-sampling.
3. Split the dataset into training and testing sets.
4. Train a Logistic Regression model.
5. Evaluate the model on both the training and testing sets.

## Expected Results

The script will output the following metrics:

- **Training Data Accuracy:** The model's accuracy on the training set.
- **Test Data Accuracy:** The model's accuracy on the testing set.

Example results:

- Training data accuracy: 0.94
- Test data accuracy: 0.92

## Dataset

The dataset used in this project is available on Google Drive. You can download it using the following link:

[Download Dataset](https://drive.google.com/file/d/1rRogMGc0D9QqR9Zhszw54tBpsFG4gcNR/view?usp=sharing)
