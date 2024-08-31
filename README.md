# 🛡️ Credit Card Fraud Detection with Machine Learning

## Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset used contains anonymized features and is labeled with whether a transaction is fraudulent or not. The objective is to build a model that accurately identifies fraudulent transactions, helping to mitigate financial fraud.

## Table of Contents

- 🛡️ Credit Card Fraud Detection with Machine Learning
- 📊 Data Overview
- ⚙️ Data Preprocessing
- 🧠 Model Training and Evaluation
- 📈 Results and Analysis

## Data

The dataset consists of 31 columns:
- **28 anonymized features** derived from PCA transformations.
- **3 named columns**:
  - `Time`: The number of seconds elapsed between this transaction and the first transaction in the dataset.
  - `Amount`: The transaction amount.
  - `Class`: The target variable, where `0` indicates a genuine transaction and `1` indicates a fraudulent one.

## Installation

To run this notebook, ensure you have the following Python libraries installed:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`
- `shap`
- `optuna`

You can install these dependencies using:

## Usage

1. **Load the Dataset**: The data is loaded from [a CSV file](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
2. **Preprocess the Data**: Handle missing values, scale features, and prepare data for model training.
3. **Train the Model**: Use machine learning algorithms (e.g., XGBoost) to train a model on the dataset.
4. **Evaluate the Model**: Assess the model's performance using metrics like accuracy, precision, recall, and ROC-AUC.

## Model Training and Evaluation

The notebook includes steps to:
- Train various machine learning models.
- Tune hyperparameters using `Optuna`.
- Evaluate the models using metrics such as accuracy, precision, recall, and ROC-AUC.

## Results and Analysis

Visualizations and metrics are provided to assess the performance of the trained models, focusing on how well the model distinguishes between fraudulent and genuine transactions.

## Conclusion

This project demonstrates the use of machine learning in detecting credit card fraud, providing a foundation for building robust fraud detection systems.


### 🚀 About Me
#### Hi, I'm Anil! 👋
I am a Data Science Enthusiast
