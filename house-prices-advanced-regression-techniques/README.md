# Prediction of House Prices README README

### Authors
Murtadha

Farah

### Date

24th-Mar-2019

### Website

### Kaggle score

6.2

---


### Problem Statement


Predict sales prices in Iowa state based on the giving data set describing the sale of individual residential property in Ames,Iowa from 2006 to 2010 compiled by Dean De Cock for use in data science education to give the best sales price prediction

SOURCE: [Kaggle](https://www.kaggle.com/c/titanic)


---


### Executive Summary

We started this project by importing the data in its raw format that contains 2930 observations and a large number of explanatory variables (23 nominal, 23 ordinal, 14 discrete, and 20 continuous) involved in assessing home values. then we did the necessary cleaning to it's values and structure.We next ship these cleaned tables to a Python friendly data type.From this stage we were ready to start. First of all , we start by investigating the df using pandas method. Secondly, we assigned our predctior (target) to Y and took the correlation using heatmap from sklearn of the whole df to determine the x's.after this we start we did a matrix on the correlation based on the Y , after we did the train_test_split and we did LinearRegression wee did the fit on it , take out the R2 score , doing kfold to test our model, final using cross_val_predic to predict the prices.

---

### Data Dictionary

| Features     | Type  | Dataset      | Description                                                            |
|--------------|-------|--------------|------------------------------------------------------------------------|
| OverallQual  | int64 | house_prices | Rates the overall material and finish of the house                     |
| GrLivArea    | int64 | house_prices | Above grade (ground) living area square feet                           |
| GarageCars   | int64 | house_prices | Size of garage in car capacity                                         |
| GarageArea   | int64 | house_prices | Size of garage in square feet                                          |
| TotalBsmtSF  | int64 | house_prices | Total square feet of basement area                                     |
| 1stFlrSF     | int64 | house_prices | First Floor square feet                                                |
| BsmtFullBath | int64 | house_prices | Basement full bathrooms                                                |
| TotRmsAbvGrd | int64 | house_prices | Total rooms above grade (does not include bathrooms)                   |
| YearBuilt    | int64 | house_prices | Original construction date                                             |
| YearRemodAdd | int64 | house_prices | Remodel date (same as construction date if no remodeling or additions) |
---
