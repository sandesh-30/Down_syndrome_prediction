# Machine-learning-classification
### Problem statement
Prediction of Down syndrome in mice by using various machine learning algorithms for classiffication with the help of available Genotype data

## Problem Description
This project is for predicting "Genotype" of mice which lead to down syndrome based on expression level of 77 different proteins. It is a binary classification problem. Three different types of ML algorthms viz. logistic regression with L1 regularizaiton, support vector machines and random forest classification are used. Data exploration, visualization and preprocessing were done prior to use classification algorithms. Implementation of all ML algorithms, data preprocessing and hyperparameters selection were done using inbuilt function from scikit learn library in python.

### Dataset
CLick here for dataset 👉 [dataset](https://archive.ics.uci.edu/ml/datasets/Mice+Protein+Expression#)

## Exploratory Data Analysis
It was found that there are certain values missing in the given data. Multivariate Feature Imputation is used to estimate these missing values.
High correlation between some features were found. Only one of the highly correlated features was kept and others were dropped (Feature Reduction)

## Preprocessing
Features were normalized prior to prediction using standard scaler from sklearn preprocessing module.

## Hyperparameter selection
Grid search over range of hyperparameters was done and best parameters was selected using F1 scoring on training data.

## Algorithms used
* Logistic regression with L1 regularization.
* Support vector classification.
* Random forest classification.

## Key features
** Performed EDA and implemented Random Forest, SVM, Logistic Regression models to predict down syndrome in mice
** Identified correlation among features,and performed missing imputation and outlier detection on 77 different features 
** Applied Grid search for hyper parameter tuning to get the best parameters for  all machine learning models

Thanks for visiting ❤️ [Sandesh Gaikwad](https://github.com/sandesh-30/)
