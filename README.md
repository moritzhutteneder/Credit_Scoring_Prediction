# Credit_Scoring_Prediction

## Introduction
This project aims to utilize a customer's financial transactions and current financial status to predict credit risk and forecast potential defaults. The dataset contains data about 1000 customers with 84 features, including both numerical and categorical variables. The main objectives are to predict whether a customer will default (classification) and to forecast the customer's credit score (regression).

## Data Exploration
The dataset consists of various features extracted from customers' financial transactions and current financial status. These features include income, savings, debt, and various ratios related to these financial metrics, along with categorical features like gambling category, debt status, credit card ownership, etc.

## Key Features
- **Data Exploration**: Initial exploration of the dataset, including summary statistics and visualizations of the target variable distribution.
- **Data Preprocessing**: Handling of numerical and categorical data using pipelines.
- **Model Building**: Construction of an MLPClassifier pipeline and hyperparameter tuning using GridSearchCV.
- **Model Evaluation**: Evaluation of the classifier on test data and visualization of results.
- **Denoising Autoencoder**: Implementation of a denoising autoencoder for dimensionality reduction and feature extraction.

## How to Use
1. **Install Requirements**: Ensure all required packages are installed by running:
   ```bash
   pip install -r requirements.txt
