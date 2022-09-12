# Credit Risk Analysis

## Overview of the Analysis

The purpose of this analysis is to predict if a borrower is creditworthy based on an original dataset versus a resampled dataset. 
The financial information used was lending data that includes:
* Size of loan 
* Interest rate
* Borrows income
* Debt to income ratio
* Derogatory marks
* Total debt
* Current loan status
The logistic regression model is used to predict if a loan will be a high risk loan (1) or a healthy loan (0). The logistic regression model is then used with a resampled dataset to identify if a loan is high risk or healthy. 


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Balanced accuracy of 95%
  * Precision of 100% for healthy loans and 85% for high risk loans.
  * Recall of 99% for healthy loans and 91% for high risk loans.


* Machine Learning Model 2:
  * Balanced accuracy of 99%
  * Precision of 100% for healthy loans and 84% for high risk loans.
  * Recall of 99% for both healthy and high risk loans.

## Summary

With a balanced accuracy score of 99% I believe model 2 will work better for finding high risk loans. It's far more important to find high risk loans than it is to find healthy loans. If more loans are healthy then there wont be an issue with them, but the high risk loans likely will be more likely to default. I would reccomend model 2 based on the balanced accuracy score.

