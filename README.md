# Bluebook Bulldozer Price Regression

This project involves predicting the auction sale price of heavy equipment using 
machine learning models. The dataset is from Kaggle's Bluebook for Bulldozers competition, 
which provides a rich set of data for training and testing regression models.

# Project Overview

The main objective of this project is to build a predictive model that accurately estimates 
the price of bulldozers. 

# Dataset

The data is downloaded from Kaggle - Bluebook for Bulldozers competition:
https://www.kaggle.com/c/bluebook-for-bulldozers/data

There are 3 datasets:

1. **Train.csv**: Historical bulldozer sales examples up to 2011 (close to 400,000 examples with 50+ different attributes,
including SalePrice which is the target variable).
2. **Valid.csv**:  Historical bulldozer sales examples from January 1 2012 to April 30 2012 (close to 12,000 examples with
the same attributes as Train.csv).
3. **Test.csv**: Historical bulldozer sales examples from May 1 2012 to November 2012 (close to 12,000 examples but missing
the SalePrice attribute, as this is what it has to be predicted).

# Library Used

This project was implemented using the following Python libraries:

* **Pandas**: For data manipulation and analysis.
* **NumPy**: For numerical computing.
* **Matplotlib**: For data visualization.
* **Scikit-learn**: For model building and evaluation.

# Exploratory Data Analysis
Exploratory analysis has been conducted to understand the data and identify potential patterns.
This involved:
* Handling missing data.
* Visualizing important features.
* Investigating the correlation between features.

# Modeling
Random Forest Regressor has been implemented and evaluated in this project.

# Model Tuning
Hyperparameter tuning was conducted using `RandomizedSearchCV` to optimize the model's performance.

# Evaluation
Kaggle has set the evaluation metric to being root mean squared log error (RMSLE). 
For this evaluation method, a function has been created within the project.





   
