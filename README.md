# Bulldozer-Price-Prediction
Machine Learning model for Bulldozer Price Prediction
# contents
## Problem Defination
## Dataset
## Extracted insights from data
## Modelling
## Evaluation

## 1.Problem Defination
how well we can predict the future sale price of bulldozar from the previous data.

## 2.Dataset
the data is downloaded from kaggle bluebook for bulldozers competition:https://www.kaggle.com/c/bluebook-for-bulldozers/overview
this data has mainly 3 datasets

Train.csv is the training set, which contains data through the end of 2011.

Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.

Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.

## Extracted insights from data

1)sale price distribution

![sale price distribution](https://user-images.githubusercontent.com/69007287/89128571-3399c880-d514-11ea-8f03-9372b2a29adb.png)

2)sale date vs sale price

![sale date vs sale price](https://user-images.githubusercontent.com/69007287/89128597-5d52ef80-d514-11ea-8e38-ee8540c45136.png)


3)important features of the data


![important features](https://user-images.githubusercontent.com/69007287/89128616-82476280-d514-11ea-90dc-c5f66b36679e.png)

## Modelling:
for this problem RandomForestRegressor algorithm is used. with the help of RandomizedSearchCV best Parameters for algorithm is found.

## Evaluation:
for this problem i created custom evaluation function which predicts

1)mean absolute error

2)root mean squared error 

3)r2
