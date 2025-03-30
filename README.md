# Bulldozer_price_predict_model
Time series model to predict the Bluebook price of bulldozers

🚜 Predicting the Sale Price of Bulldozers using Machine Learning
In this notebook, we're going to go through an example machine learning project with the goal of predicting the sale price of bulldozers.

## 1. Problem defintion
How well can we predict the future sale price of a bulldozer, given its characteristics and previous example of how much similar bulldozers have been sold for?

## 2. Data
The data is downloaded from the Kaggle Bluebook for Bulldozers competition:

https://www.kaggle.com/competitions/bluebook-for-bulldozers

The data for this competition is split into three parts:

Train.csv is the training set, which contains data through the end of 2011.

Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.

Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.

## 3. Evalution
The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

For more on the evaluation of this project check:

www.kaggle.com/competitions/bluebook-for-bulldozers/overview/evaluation

Note: The goal for most regression evaluation metrics is to minimize the error. For ecample, our goal for this project will be to build a machine learning model which minimizes RMSLE.

## 4. Features
Kaggle provides a data dictionary detailing all of the features of the dataset. You can view this data dictonary on Google sheets:

https://docs.google.com/spreadsheets/d/1XiQEYLCSyjbjicAHfNvs-1d7gjYQ4MK_xxkU5TAjL1k/edit?usp=sharing

# How to setup environment:

Use Anaconda or Miniconda to set up the ./env folder and install the requirments using the `environment.yml` file.
