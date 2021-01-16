House Price Prediction 
DATASET: The Boston Housing Dataset is a derived from information collected by the U.S. Census Service concerning housing in the area of Boston MA. 

METHOD The data has been viewed as a regression problem and the following algorithims have been employed :

- Linear Regression
- Decision Tree
- Random Forest
- XGBoost
- Adaptive Boosting with Random forest

CONCLUSIONS

- Inflation has been taken into account the prices of houses have been adjusted. 
- Of all the imputation methods, knn works the best method for this dataset, hence it has been used for imputation.
- Using feature engineering the number of features were reduced to three namely, PTRATIO, LSTAT, and RM
- XGBoost performs the best in making predictions with an RMSE error of 15.5 and R2 error of 79.4.
