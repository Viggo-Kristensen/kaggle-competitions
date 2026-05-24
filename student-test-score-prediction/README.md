## Overview

This project is my solution to the Kaggle competition *"Predict Student Test Scores"*.
The goal is to predict what test score a student gets on a scale from 0-100.

## Approach

* **Data cleaning**

  * Replaced missing numerical values with the median
  * Replaced missing categorical values with `"most_frequent"`
  
  * Used OneHotEncoder for categorical data
  * Used Ordinal encoder for categorical data with a meaningful ranking

* **Feature engineering**

  * Used the competition winner's custom features which were created using genetic programming.

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



