# E-Commerce Purchase Intention Prediction (ML)

## Overview
This project predicts whether a customer will make a purchase based on their browsing behavior using machine learning.

## Problem Statement
Classify whether a user session results in a purchase (Revenue = 1) or not.

## Features
- Page visits and duration
- Bounce rates and exit rates
- User type and session details
- PageValues (key predictor)

## Approach
- Data preprocessing and feature engineering
- Handling categorical variables and scaling
- Built ML pipeline with:
  - MinMaxScaler
  - SMOTE (for class imbalance)
  - SelectKBest (feature selection)

## Models Used
- Decision Tree
- Random Forest
- SVM
- MLPClassifier (best model)

## Evaluation
- Accuracy: ~88%
- ROC-AUC used for model comparison

## Key Insight
- PageValues was the strongest predictor of purchase behavior

## Tech Stack
- Python
- Pandas
- Scikit-learn
- Imbalanced-learn (SMOTE)

## Run Locally
```bash
pip install -r requirements.txt
