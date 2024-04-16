# credit-risk-classification



## Overview 

The objective of this project is to develop a machine learning algorithm capable of classifying credit risk. This classification helps in assessing the creditworthiness of loan applicants by categorizing loans as either healthy or high-risk.

##Dataset

The dataset contains 77,536 records, divided as follows:

* Train Data: 58,152 records
* Test Data: 19,384 records

## Features and Target

# Features
* Loan Size
* Interest Rate
* Borrower Income
* Debt-to-Income Ratio
* Number of Accounts
* Derogatory Marks
* Total Debt

## Target
* Loan Status: Indicates the health of the loan (0 for Healthy Loan, 1 for High-Risk Loan).


## Model Development Steps

1- Load Data: Import data into a DataFrame.
2- Prepare Data: Isolate loan_status as the label and use the remaining columns as features.
3- Split Data: Divide the data into training and test datasets.
4- Model Training: Fit a logistic regression model using the training data.
5- Predictions: Use the fitted model to predict loan status on the testing data.
6- Evaluation: Assess model performance using a confusion matrix and a classification report.

## Results

# Logistic Regression Model
* Accuracy Score: 99%

Metrics for Healthy Loan (Label 0)
* Precision: 1.00
* Recall: 0.99
* F1 Score: 1.00

Metrics for High-Risk Loan (Label 1)
* Precision: 0.84
* Recall: 0.94
* F1 Score: 0.89

## Summary

The Logistic Regression model was selected due to its superior accuracy, precision, recall, and F1 score values for both healthy and high-risk loans. This model is particularly effective in prioritizing the accurate identification of high-risk loans, which is crucial for mitigating potential financial losses.

## Technologies Used

* Python
* Pandas
* Scikit-Learn

## How to Run

Include instructions on how to set up and run the model, including any required packages or dependencies.

## Conclusion

The Logistic Regression model demonstrates high effectiveness in classifying credit risks, with excellent performance metrics across both categories of loans. Future improvements could include exploring more complex models like Gradient Boosting Machines (GBM) to potentially enhance predictive performance.
