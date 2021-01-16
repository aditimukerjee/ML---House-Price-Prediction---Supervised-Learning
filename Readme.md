House Price Prediction 
DATASET: The Boston Housing Dataset is a derived from information collected by the U.S. Census Service concerning housing in the area of Boston MA. 
The following describes the dataset columns:

CRIM - per capita crime rate by town /n
ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
INDUS - proportion of non-retail business acres per town.
CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
NOX - nitric oxides concentration (parts per 10 million)
RM - average number of rooms per dwelling
AGE - proportion of owner-occupied units built prior to 1940
DIS - weighted distances to five Boston employment centres
RAD - index of accessibility to radial highways
TAX - full-value property-tax rate per $10,000
PTRATIO - pupil-teacher ratio by town
B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
LSTAT - % lower status of the population
MEDV - Median value of owner-occupied homes in $1000's

METHOD The data has been viewed as a regression problem and the following algorithims have been employed.

-Linear Regression
-Decision Tree
-Random Forest
-Xbg
-Adaptive Boosting with Random forest

CONCLUSIONS

Inflation has been taken into account the prices of houses have been adjusted. - Of all the imputation methods, knn works the best method for this dataset, hence it has been used for imputation.

Using feature engineering the number of features were reduced to three namely, PTRATIO, LSTAT, and RM
XGBoost performs the best in making predictions with an RMSE error of 15.5 and R2 error of 79.4.
