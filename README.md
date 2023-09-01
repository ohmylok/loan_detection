# House_loan_detection

This project aims to detect potential house loan fraud cases based on historical data. Dataset comes from Kaggle, with over 300 thousand tuples and over 110 features. 

This repository focuses on house loan fraud detection based on XGBoost algorithm. Facing extremely imbalanced dataset, this project applies resample method. Besides, using Boruta variables selection algorithm to select important varibales to reduce dimensions. For hyperparameters tuning issue, this project uses Bayes search algorithm to detect the best set of parameters which will obtain the best ROC score.
