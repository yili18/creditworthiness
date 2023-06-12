# Creditworthiness of borrowers

## This project is to build a model that can identify the credit risk of borrowers for a peer-to-peer lending services company.

* The purpose of this analysis is to build a model that can identify the creditworthiness of borrowers using historical lending activity data from a peer-to-peer lending services company. 
* The dataset contains information about loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status. The loan status indicates whether a loan is healthy (0) or has a high risk of defaulting (1). Need to predict the credit risk of the borrowers       based on the laon statua.
* The variables to predict: `value_counts`, `accuracy score`, `confusion matrix`, `classification report`
* The stages of the machine learning process: The model stage, the fir stage, the predict stage and the evaluation stage
* Methods: `LogisticRegression`, `RandomOverSampler`

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  * Accuracy Score: 0.9520
  * It achieves a high precision of 1.00 for the 0 label, indicating that all instances classified as healthy loans are true negatives. For the 1 label, the precision is 0.85, meaning that 85% of the instances classified as high-risk loans are true positives.
  * The recall for the 0 label is 0.99, indicating that the model correctly identifies 99% of the healthy loans. The recall for the 1 label is 0.91, indicating that the model correctly identifies 91% of the high-risk loans.

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  * Accuracy Score: 0.9937
  * It achieves a high precision of 1.00 for the 0 label, indicating that all instances classified as healthy loans are true negatives. For the 1 label, the precision is 0.84, meaning that 84% of the instances classified as high-risk loans are true positives. 
  * The recall for the 0 label is 0.99, indicating that the model correctly identifies 99% of the healthy loans. The recall for the 1 label is 0.99, indicating that the model correctly identifies 99% of the high-risk loans.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use:
* Comparing the two versions of the dataset predictions, the logistic regression model trained with oversampled data performs exceptionally well. It achieves higher precision, recall, and F1 scores for both the 0 and 1 labels. This indicates that the model trained with oversampled data has a better balance.
