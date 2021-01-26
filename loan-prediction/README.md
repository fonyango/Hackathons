# Loan-Prediction
Loan Prediction Challenge

## About Company
Dream Housing Finance company deals in all home loans. They have presence across all urban, semi urban and rural areas. Customer first apply for home loan after that company validates the customer eligibility for loan.

## Problem
Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers. Here they have provided a partial data set.


 
### Note: 

Evaluation Metric is accuracy i.e. percentage of loan approval you correctly predict. 
Extracted from https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/

## Project Flow
- I worked through the project as follows:
- Importing required libraries
- Reading both the train data and test data
- Explored both datasets simulteneously
- Imputed missing data in both the datasets
- Concatenated the datasets and created dummies for categorical data
- Split the dataset and trained the model
- Used hyper parameter tuning with RandomizedSearchCV
- Used XGBoost model to fit and predict the Loan_Status

## Score

I got an accuracy score of **0.75694**. 
