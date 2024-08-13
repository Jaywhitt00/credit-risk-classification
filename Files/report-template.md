# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose of this analysis is to predict credit risk for peer to peer using machine learning.
The data included loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, total debt and loan status.

* Explain what financial information the data was on, and what you needed to predict.
I needed to predtict if the loan was healthy or not.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

* Describe the stages of the machine learning process you went through as part of this analysis.

The stages of this machine learning :

Split the datasets for training and testing
Create and fit a logistic regression model with data
Evaluate the model's performance by observing accuracy, precision, recall, and f1 scores
Resample the data with Random Over Sampler for class imbalance
Create and fit a secondary logistic regression model with resampled data
Evaluate the secondary model's performance by observing the same accuracy, precision, recall, and f1 scores



## Results

logistic regression model was fit to the resampled data. Finally, the predictions of the resampled model were compared to the given results.



Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

Accuracy:99.6
Precision: 99%

Healthy Loans- 1.00
High-Risk Loans- .87

Recall:

Healthy Loans- 1.00
High-Risk Loans- .89

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

The better model to use Model 2
The results show that it can better assess a higher difference when comparing healthy loan applications to high-risk loan applications, and avoid making loans that will lead to greater loss in the future.

If you do not recommend any of the models, please justify your reasoning.
