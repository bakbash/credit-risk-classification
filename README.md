# credit-risk-classification



## Overview 

Purpose:
The purpose of this analysis is to develop a machine learning algorithm to classify credit risk as either a healthy or high-risk loan.This helps companies in assessing the creditworthiness of applicants.

Features: loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. 
Target: loan_status.


 * Dataset: 77,536
 * Train Data:58,152
 * Test Data:19,384



Steps:(LR model)

Load data into a dataframe.

Create loan_status as labels and use the other columns as features.

Split the data into training and test datasets.

Fit a logistic regression model using the training data.

Save the predictions on the testing data labels by using the testing feature data and the fitted model.

Evaluate the model’s performance by generating a confusion matrix and printing the classification report.




## Results
logistic regression Model,Accuracy Score:0.99


## Healthy Loan (0) :
* Precision: 1.00
* Recall: 0.99
* F1:1.00


## High-Risk Loan (1):
* Precision: 0.84
 * Recall: 0.94
 * F1:0.89


## Summary

I recommend  Logistic Regression model  because of its higher accuracy, precision,  recall  and  F1 score values for both healthy and high-risk loans .
The performance of the model depends on the specific problem we are trying to solve. In this case, achieving high precision and recall values for high-risk loans is more significant than for healthy loans.


