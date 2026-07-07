## Overview

This project is my solution to the Kaggle competition *"Predicting Loan Payback"*.
The goal is to predict whether or not a borrower will pay back their loan.

## Approach

* **Data cleaning**

  * Replaced missing numerical values with the median
  * Replaced missing categorical values with `"most_frequent"`
  * Used OneHotEncoder for categorical data

* **Feature engineering**
  * Performed a permutation importance analysis to deduct the raw features that were the best predictors.

  * Feature engineering choices were found through a bruteforce validation loop trying different operations between feature pairs created from the 3 best performing in the permutation importance analysis.
    
* **Model**

  * XGBoost for classification

## Results

* ROC AUC: **0.92481**
* Kaggle placement: **#861**

## How to Run

1. Upload `kaggle.json`
2. Run all notebook cells

## Output

The notebook generates:
`submission/submission.csv`




