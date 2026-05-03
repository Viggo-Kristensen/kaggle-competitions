## Overview

This project is my solution to the Kaggle competition *"Spaceship Titanic"*.
The goal is to predict which passengers were transported to another dimension based on personal and behavioral data.

## Approach

* **Data cleaning**

  * Replaced missing numerical values with the median
  * Replaced missing categorical values with `"unknown"`

* **Feature engineering**

  * Created a new column `TotalSpend` by summing:
    `RoomService`, `FoodCourt`, `ShoppingMall`, `Spa`, `VRDeck`
  * Split the `Cabin` column into three features: `Deck`, `Num`, `Side`

* **Model**

  * Logistic Regression

## Results

* Accuracy: **78.7%**
* Kaggle placement: **#1858**

## How to Run

1. Upload `kaggle.json`
2. Run all notebook cells

## Output

The notebook generates:
`submission/submission.csv`


