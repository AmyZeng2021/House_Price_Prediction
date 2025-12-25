# Ames House Price Prediction
## Problem Statement :

Ames House Price Prediction is a Python machine learning project on housing data from Ames, Iowa.


## Goal : 

This project is intended to set up a machine learning model using the train set to predict the sales price for each house in the test set. Root Mean Squared Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price was used as the accuracy metric.

## Data Source : 

The data was downloaded from: https://www.kaggle.com/c/house-prices-advanced-regression-techniques

## Exploratory Data Analysis

Exploratory Data Analysis (EDA) were conducted to understand: a. Price distribution b. Feature correlations c. Outliers and trends.

## Modelling strategy

A large range of commonly used machine learning models were employed, including: Linear Regression, Logistic Regression, Ridge Regression, Lasso Regression, Elastic Net, Random Forest, Gradient Boosting Machine (GBM), AdaBoost, XGBoost, LightGBM, CatBoost, k-Nearest Neighbors (k-NN), SVR, PCA etc.

### Table of Contents

The analyses are presented in two notebooks:
- *[Exploratory Data Analysis and Model Training](https://github.com/AmyZeng2021/House_Price_Prediction/blob/main/Ames-house-price-EDA.ipynb)*
- *[Model Development](https://github.com/AmyZeng2021/House_Price_Prediction/blob/main/Ames-House-Price-Prediction-v4.ipynb)*
  
## Model Evaluation 
***Evaluation Metrics***:

```
		          Train Score	Train MSE	Train RMSE	Test Score	Test MSE	Test RMSE
Blended Model	98.55%		  0.0023		0.04796		  93.34%		  0.0111		0.10536
SVR		        93.42%		  0.0104		0.10198		  91.92%		  0.0135		0.11619
GBM		        100.00%		  0.0000		0.00000		  91.12%		  0.0148		0.12166
ADA		        99.98%		  0.0000		0.00000		  90.70%		  0.0155		0.12450
Random Forest	98.17%		  0.0029		0.05385		  90.46%		  0.0159		0.12610
ElasticNet	  95.17%		  0.0076		0.08718		  90.30%		  0.0161		0.12689
Lasso		      95.20%		  0.0076		0.08718		  90.28%		  0.0162		0.12728
XGBoost		    100.00%		  0.0000		0.00000		  90.21%		  0.0163		0.12767
Ridge		      95.32%		  0.0074		0.08602		  89.91%		  0.0168		0.12961
LightGBM	    100.00%		  0.0000		0.00000		  89.87%		  0.0169		0.13000
Linear Model	94.67%		  0.0084		0.09165		  89.31%		  0.0178		0.13342
Cat Boost	    95.34%		  0.0073		0.08544		  88.29%		  0.0195		0.13964
Decision Tree	98.27%		  0.0027		0.05196		  11.47%		  0.1474		0.38393
PCA-KNN		    -12.63%		  0.1774		0.42119		  -10.72%		  0.1843		0.42930
PCA-Linear	  92.46%		  0.0119		0.10909		  -15.23%		  0.1918		0.43795
```


