# Credit Risk Prediction Project

## Overview

This project applies Machine Learning classification algorithms to predict customer credit card approval based on demographic, financial, and behavioral attributes.
The dataset contains 690 records with 15 features such as age, income, debt, employment, credit score, and prior defaults.

## Objective

* Predict whether a customer’s credit card application will be approved (Yes/No).
* Identify the most reliable model for credit risk prediction.
* Help lenders classify applicants into low-risk or high-risk groups.

## Dataset

* Instances: 690
* Features: 15 + 1 target (Approved)
* Target Variable: Approved (0 = Rejected, 1 = Approved)

## Best Model

Random Forest achieved the highest accuracy of **87.31%**.
Other ensemble models such as AdaBoost, Gradient Boosting, and Bagging also performed well, but Random Forest gave the most reliable results.

## Key Results

* Random Forest provided the highest classification accuracy.
* Ensemble methods consistently outperformed simpler models.
* Credit Score, Employment, and Prior Default were strong predictors of approval.

## Future Scope

* Hyperparameter tuning and feature engineering.
* Adding macroeconomic indicators for deeper insights.
* Trying LSTM/GRU for time-series credit risk prediction.

## Business Impact

* Reduced default risk by identifying high-risk applicants.
* Optimized approvals for low-risk customers.
* Cost savings through automated risk assessment.

## Resources

Google Colab Notebook:
[https://colab.research.google.com/drive/1Bu3u9zqhsKDRsBOu2ryE4cs1lI2MBeRG?usp=sharing](https://colab.research.google.com/drive/1Bu3u9zqhsKDRsBOu2ryE4cs1lI2MBeRG?usp=sharing)

*"From raw data to refined classes — shaping decisions with precision."*
