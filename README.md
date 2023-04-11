# Credit Risk Analysis Report

## Overview of the Analysis

## Background
The purpose of the analysis was to identify the creditworthiness of borrowers of loans by predicting if a loan is healthy (0) or high risk (1). A dataset of historical lending activity from a peer-to-peer lending services company was utilised. 

Machine learning process steps:
A labels set (y) from the “loan_status” column and features (X) dataFrame was created.
The balance was then checked of the labels variable (y) by using the value_counts function. 
The data was then split into training data and testing data by using train_test_split. 
Training data was then fitted to a Logistic Regression Model. 
A prediction was made and the models performance was evaluated.
RandomOverSampler from the imbalanced-learn library was used to resample the data. 
This data was then fitted to a Logistic Regression Model. 
A prediction was again made and the new models performance evaluated.

## Results
* Machine Learning Model 1:
  * Balanced Accuracy Score= 0.95 (to 2 decimal places)
  * Precision: Healthy loan =1.00, High risk loan=0.85 
  * Recall scores: Healthy loan =0.99, High risk loan=0.91
  
* Machine Learning Model 2:
  * Balanced Accuracy Score= 0.99 (to 2 decimal places)
  * Precision: Healthy loan =1.00, High risk loan=0.84 
  * Recall scores: Healthy loan =0.99, High risk loan=0.99

## Summary
Machine Learning Model 2 appears to perform the best as the balanced accuracy score was higher for this model. I would therefore use it to make predictions with regards to healthy or non-healthy loans.


References
1 Code for random over sampler & logistic regression classifier https://github.com/Mun-Min/Credit_Risk_Classification/blob/main/credit_risk_resampling.ipynb

2 Data Analytics Bootcamp Resources
