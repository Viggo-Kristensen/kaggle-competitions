## Overview

This project is my solution to the Kaggle competition *"Spaceship Titanic"*.
The goal is to predict which passengers were transported to another dimension based on personal and behavioral data.

## Approach

* **Data cleaning**

  * Replaced missing numerical values with the median
  * Replaced missing categorical values with `"most_frequent"`
  
  * Used OneHotEncoder for categorical data
  * Used Ordinal encoder for categorical data with a meaningful ranking

* **Feature engineering**

  * Used the competition winners custom features which were created using genetic programming.

* **Model**

  * XGBoost for regression

## Results

* RMSE: **8.708%**
* Kaggle placement: **#922**

## How to Run

1. Upload `kaggle.json`
2. Run all notebook cells

## Output

The notebook generates:
`submission/submission.csv`



