## Overview

This project is my solution to the Kaggle competition *"Predicting Stellar Class"*.
The goal is to classify stars, galaxies and quasars based on their spectral characteristics

## Approach

* **Data cleaning**

  * Replaced missing numerical values with the median
  * Replaced missing categorical values with `"most_frequent"`
  * Used OneHotEncoder for categorical data
  * Encoded the target classes using labelencoder

* **Feature engineering**

  * Created custom features by combining the most useful features from the permutation importance test.
* **Model**

  * XGBoost for classification

## Results

* Balanced accuracy: **0.9576**
* Kaggle placement: **#1123**

## How to Run

1. Upload `kaggle.json`
2. Run all notebook cells

## Output

The notebook generates:
`submission/submission.csv`



