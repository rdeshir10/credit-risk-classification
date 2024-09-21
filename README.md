# Credit Risk Classification Report

## Overview of the Analysis

* The purpose of this analysis is to create a machine learning model that can effectively predict the creditworthiness of a borrower.  
* The financial information included details of the borrower such as (loan_size, interest_rate,borrower_income,debt_to_income,num_of_accounts,derogatory_marks,total_debt) that can help identify whether or not granting a loan would be risky or not. 
* The outcome we aim to predict is whether a loan is high-risk or not.
* Divided into training and testing sets using train_test_split. Chose logistic regression to classify loan risk. Trained the logistic regression model on the training data. Predicted loan status using the test data. Assessed model accuracy,     
  precision, and recall using confusion matrix and classification report.

## Results

- Accuracy: The model's accurracy score of 0.992 suggests that 99% of the predictions made were correct.

- Precision: The precision score for healthy loans is 1.00, indicating 100% accuracy. On the other hand High-Risk Loans have a score of  0.84, meaning that 84% of the loans predicted as "High-Risk" were actually high-risk, with 16% being false positives.
- Recall: The recall score for healthy loan is 0.99, meaning that 99% of the actual healthy loans were correctly identified. Whereas the recall score for high-risk loan  is 0.94, meaning that 94% of the actual high-risk loans were correctly identified by the               
          model, and only 6% were missed (false negatives).

## Summary

The Logistic Regression model achieved 99% accuracy with strong recall (94%) for high-risk loans, making it reliable in identifying risky cases. Although the precision for high-risk loans is 84%, the model’s high recall makes it effective for minimizing missed risks. I recommend the model due to its accuracy and ability to identify high-risk loans effectively.
