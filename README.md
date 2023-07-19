# credit-risk-classification

## Overview of the Analysis

The purpose of the analysis is to identify the creditworthiness of the borrowers base on the dataset of historical lending activity from a peer-to-peer lending services company. We will build and train a machine learning model based on the loan risk.

Financial informations data needed to predict include:
- Size of the loan
- Interest rate
- Borrower’s income
- Debt to income ratio
- Total number of account held by borrower
- Derogatory marks against the borrower
- Total amount of debt
- Loan status

The dataset was split and put into training and testing datasets using train_test_split. We will use the training dataset to build the logistic regression model using LogisticRegression module. We will then applied the logistic regression model to the testing dataset and make the prediction. The purpose of the model is to determine if the borrower is consider a high risk (1) or a low risk (0) borrower.



## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model:
  * Accuracy: 94%
  * Precision: 94% (Based on the average of 100% low risk prediction and 87% high risk prediction)
  * Recall: 95% (Based on the average of 100% low risk prediction and 89% high risk prediction)

## Summary

Based on the result above, I think the current model fit the purpose to identify the creditworthiness of the borrowers as the accuracy level is only 94% and the recall level is only 95%.
