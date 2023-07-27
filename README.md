# bulldozer-price-regression
Predicting the sale price of Bulldozers 


Predicting the sale price of bulldozers using machine learning
In this notebook ,we're going to thorigh an example machine learning project with the goal of predicting the sale price of bulldozers.

### 1.Problem definition
How well can we predict the future sale price of a bulldozer,given its characteristsics and previous examples of how much similar bulldozers have been sold for?

### 2. Data
The data is downloaded from the Kaggle Blue Book for bulldozers competition:https://www.kaggle.com/c/bluebook-for-bulldozers/data

There three main datasets:

* Train.csv is the training set, which contains data through the end of 2011.
* Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
* Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.

### 3. Evaluation
The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

For more on the evaluation of this project check: https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation

Note: The goal for most regression evaluation metrics is to minimize the error.For example ,our goal for this project will be to build a machine learning model which minimises RMSLE.

### 4. Features
Kaggle provides a data dictionary detailing all of the features of the dataset.You can view this data dictionary here:

https://www.kaggle.com/c/bluebook-for-bulldozers/download/Data%20Dictionary.xlsx
