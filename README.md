# Car Price Prediction with Dummy Variables and One Hot Encoding

## Overview
This repository contains code for a linear regression model with both dummy variables and one hot encoding method to predict car prices based on historical data. The model is built using Python and the scikit-learn library.

## Dataset
The dataset used for training the model is included in the repository as `carprices.csv`. It contains the following columns:
- `Car Model`: Model of the car.
- `Mileage`: Total miles driven.
- `Sell Price($)`: Selling price in dollars.
- `Age(yrs)`: Age of the car in years.

## Dependencies
To run the code in this repository, you'll need the following dependencies:
- pandas
- scikit-learn

You can install the dependencies using pip.

## Result
I have used dummy variables with pandas and one hot encoding with sklearn library for labeling of the column ("Car Model"). The aim and results are the same, just codes are different. After every 2 processes the model score is 0.9417050937281082 which it is a good result.
