# Zillow-Home-Value-Index-Prediction

This project was a part of an assignment of the CIVE 7100: Time Series and Geospatial Data Sciences Course at Northeastern University.

The assignment was kind of like a Kaggle Competition wherein, data from Zillow HVI data for the United States was given. The task was to implement a model that most accurately predicts the missing ZHVI values in the dataset.

Grade Received: 100/100

## Problem
The problem is to predict the missing values of the Zillow Home Value Index (`zhvi`) in the dataset and assess the model using evaluation metrics like R2 score, root mean squared error, mean absolute percentage error and bias. 

## Steps
- Exploring the data - seeing data types and number of missing values.
- One Hot Encoding categorical features.
- Splitting the data: Training data is the part of the data without missing zhvi values. Validation data is the other part of the data without missing zhvi values. This split is 70-30%. Test data is the data which has missing `zhvi` values.
- Implementing Ridge Regression.
- Evaluating the model.

## Model Evaluation

Following results were observed:
- R2 score = 0.87
- RMSE = 35567.02
- Bias = 1094.67
- MAPE = 3.527
