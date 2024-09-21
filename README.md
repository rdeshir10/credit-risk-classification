# Module 12 Report Template

## Overview of the Analysis

* The purpose of this analysis is to create a machine learning model that can effectively predict the creditworthiness of a borrower.  
* The financial information included details of the borrower such as (loan_size, interest_rate,borrower_income,debt_to_income,num_of_accounts,derogatory_marks,total_debt) that can help identify whether or not granting a loan would be risky or not. 
* The outcome we aim to predict is whether a loan is high-risk or not.
* Divided into training and testing sets using train_test_split. Chose logistic regression to classify loan risk. Trained the logistic regression model on the training data. Predicted loan status using the test data. Assessed model accuracy,     
  precision, and recall using confusion matrix and classification report.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

## Results

- Accuracy: The model achieved an overall accuracy of 99%, meaning that 99% of the predictions made by the model were correct.

- Precision: The precision score is 1.00, indicating that every loan predicted as "Healthy Loan" by the model was indeed healthy. The precision score is 0.84, meaning that 84% of the loans predicted as "High-Risk" were actually high-risk, with 16% being false positives.
- Recall: Healthy Loan: The recall score for healthy loan is 0.99, meaning that 99% of the actual healthy loans were correctly identified. Whereas the recall score for high-risk loan  is 0.94, meaning that 94% of the actual high-risk loans were correctly identified by the           model, and only 6% were missed (false negatives).

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
