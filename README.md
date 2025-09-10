# VIF feature Selection Tool
A simple Python utility to detect and reduce multicollinearity in datasets using Variance Inflation Factor (VIF).

## 🚀 Features

Calculates Variance Inflation Factor (VIF) for each feature

Iteratively removes the feature with the highest VIF if above threshold

Returns a final dataframe with retained features and their VIF values

Useful for regression and machine learning preprocessing

## 📖 Theory (Quick Recap)

Variance Inflation Factor (VIF) measures how much a feature is correlated with other features.

High VIF (> 5 or 10) indicates multicollinearity, which can make regression coefficients unstable.

This utility helps automatically remove such problematic features in very easy way. It returns the names of column that are still in dataframe and can be used for model fitting. 


#### Developed by Pratham 
