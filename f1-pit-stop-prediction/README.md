## Overview

This project is my solution to the Kaggle competition *"Predict F1 Pit Stops"*.
The goal is to predict whether a f1 car is going in for a pit stop on a given lap.

## Approach

* **Data cleaning**

  * Replaced missing numerical values with the median
  * Replaced missing categorical values with `"most_frequent"`
  
  * Used OneHotEncoder for categorical data
  * Used Ordinal encoder for categorical data with a meaningful ranking

* **Feature engineering**

  * Created new features by combining the features that were the strongest predicters in the permutation importance analysis.

* **Model**

  * Logistic regression

## Results

* roc_auc_score: 0.95009 ****
* Kaggle placement: **#994**

## How to Run

1. Upload `kaggle.json`
2. Run all notebook cells

## Output

The notebook generates:
`submission/submission.csv`



