## Overview

This project is my solution to the Kaggle competition *"Predict Irrigation Need"*.
The goal is to predict the amount of irrigation required under varying environmental conditions.

## Approach

* **Data cleaning**

  * Replaced missing numerical values with the median
  * Replaced missing categorical values with `"most_frequent"`
  
  * Used OneHotEncoder for categorical data
  * Used Ordinal encoder for categorical data with a meaningful ranking

* **Feature engineering**

  * Created domain informed features by combining related environmental variables to better capture interactions between them.

* **Model**

  * RandomForest

## Results

* Balanced accuracy: **0.95901**
* Kaggle placement: **#3714**

## How to Run

1. Upload `kaggle.json`
2. Run all notebook cells

## Output

The notebook generates:
`submission/submission.csv`



