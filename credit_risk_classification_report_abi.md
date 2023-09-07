# Module 20-Supervised-Learning Report

## Overview of the Analysis

The purpose of this analysis was to try to predict whether or not a borrower will default on their loan based on factors such as:
loan size
interest rate
borrower income, debt, and the ratio thereof

The goal was to predict loan_status.

The data was read into a Pandas dataframe, split into training and testing data groups, and then fit to various models.

Models used were logistic regression and random forest. Then the data was scaled and fit to a logistic regression model again.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1 - Logistic Regression:
  Accuracy - 99%
  Precision - 87%
  Recall - 89%

* Machine Learning Model 2 - Random Forest:
  Accuracy - 99%
  Precision - 87%
  Recall - 87%

* Machine Learning Model 3 - Logistic Regression on Scaled Data:
  Accuracy - 99%
  Precision - 87%
  Recall - 98%

## Summary

The model I recommend is a logistic regression on scaled data. The Random Forest model overfits the data. The unscaled Logistic Regression model has a better recall score than the Random Forest model, but applying a scaler optimizes the model.
