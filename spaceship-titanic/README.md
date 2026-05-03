## Overview

This project is my solution to the Kaggle competition "Spaceship Titanic". The goal is to predict which passengers are transported to a different dimension. Predictions are made from a set of personal records recovered from the spaceship's damaged computer.

## Approach 

* Data cleaning
  * Replacing missing numerical values with the median
  * Replacing missing categorical data with "unknown"
* Feature engineering
  * new column "TotalSpend" that sums the money spent on RoomService, FoodCourt, ShoppingMall, Spa, VRDeck.
  * Splitting the "Cabin" column into 3 new columns Deck, Num, Side.
* Model training
  * Logistic regression

## Results

* Accuracy: 78.7%
* placement: #1858

## How to Run

1. Upload `kaggle.json`
2. Run all cells

## Output

`submission/submission.csv`
