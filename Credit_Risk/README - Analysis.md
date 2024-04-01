# Module 20 Report

## Overview of the Analysis

For this analysis, I performed a logistic regression model on the data. This can be used when there are only two possible outcomes, in this case 1 or 0 in "loan status". Other information was given including loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks and total debt. I used the model to predict if the person was provided a loan or not. 

First, I imported the data and split it into the outcome and everything else. Then, I fit the LogisticRegression model onto the testing portion of the data. Then using the data, I predicted the outcomes of the testing portion of the data. I was then able to calculate the confusion matrix and classification report.  

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

-Accuracy score: 99.24%

Loan Status = 0
-Precision score:100%
-Recall score:100%

Loan Status = 1
-Precision score: 87%
-Recall score: 89%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

This model has high accuracy, precision, and recall scores making it highly recommended to use. However, knowing that this is lending data which could create the loss of a lot of money, it might be useful to use multiple different types of models to create a more confident answer for the company who is actually putting their money on the line. 