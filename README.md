

# Implementation of Regression Algorithms 

Regression is basically a statistical approach to find the relationship between variables. In machine learning, this is used to predict the outcome of an event based on the relationship between variables obtained from the data-set.

RandomForest Regression

The Random Forest is one of the most effective machine learning models for predictive analytics, making it an industrial workhorse for machine learning.The random forest model makes the predictions by combining decisions from a sequence of base models.
There is data of stock in my CSV file (Random.csv) I split it into two sets for train and test the data.The accruracy of data with RandomForest regression is 0.99

Support vector machine regression

In SVM  we creates hyperplane this is basically the separation line between the data classes. Although in SVR we are going to define it as the line that will help us predict the continuous value or target values.The points which is closest to boundary is support vectors.I used same CSV File for SVM(Random.csv).The accuracy with SVR is 0.84

There is an implementation of SVM Regressor which is in implementSVM.ipynb file and implementation of RandomForest Regressor is in implementRandomForest.ipynb file (jupyter notebook).
