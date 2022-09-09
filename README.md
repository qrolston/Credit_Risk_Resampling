# READ ME - credit_risk_resampling.ipynb

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Purpose: To determine the health of a loan applicant (healthy=0 unhealthy=1)
* The data was based upon: loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks and total debt.
* We used train_test_split to base our model on the given data from 'lending_data.csv'. This gave us both training data and testing data
* We used LogisticRegression and RandomOverSampler to create our two machine learning models.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Balanced Accuracy Score: 95.20%
  * Precision Score: 99%
  * Recall Score: 99%


* Machine Learning Model 2:
  * Balanced Accuracy Score: 99.37%
  * Precision Score: 99%
  * Recall Score: 99%

## Summary

Both models were able to predict accurate outcomes of our data. However the oversampled data had an accuracy score that was 4% better than the first. I would recommend Machine Learning Model 2.


