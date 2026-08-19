# Online Retail Repeat-Purchase Prediction

This repository contains the reproducible analytical workflow for a postgraduate Business Analytics dissertation investigating 90-day repeat-purchase prediction using the UCI Online Retail dataset.

## Dataset
Original transactions: 541,909  
Cleaned transactions: 392,692  
Cleaned customers: 4,338  
Eligible modelling customers: 3,370  

Observation period: 1 December 2010 – 9 September 2011  
Prediction period: 10 September 2011 – 9 December 2011  

## Predictors
- Recency
- Frequency
- Monetary Value
- Unique Products
- Average Order Value
- Basket Size
- Country

## Models
- Logistic Regression
- Decision Tree
- Random Forest

## Evaluation
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion matrix
- Majority-class baseline

## Explainability
- Logistic Regression coefficients
- Odds ratios
- Random Forest feature importance
- Permutation importance

## Reproducibility
Run `repeat_purchase_analysis.ipynb` from top to bottom to reproduce the analytical workflow.
