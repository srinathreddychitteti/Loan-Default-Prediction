# Loan-Default-Prediction
In this project I used logistic regression , Support vector Machines , XGBoost to predict if a coustomer who wants to take a loan is likely to default it or not

The data was taken from Kaggle.
The data contains 10000 rows of data which was had the problem of class imbalance which means the data points belonging to Defaulted? == 1 are very less in number or were
not recorded as much.

One of the resampling method called Over Sampling was used to tackle this problem.

Since we are dealing with class imbanced data accuracy as a metric will not be effective since the probability of occurance of the less occuring class is very low.
So we use Precision , Recall , f1-Score as metrics

The logistic regression model was initially used but did not perform well with the test data. 

The Support Vector Machine with "RBF" kernal produced better reults than the logistic regression model but the metrics can be improved.

The XGBoost library was used to build a XGBoost classifier which performed better than the above two models.
