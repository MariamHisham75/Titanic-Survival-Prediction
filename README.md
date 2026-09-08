# Titanic-Survival-Prediction

##  Overview
This repository contains an end-to-end Machine Learning pipeline predicting passenger survival on the Titanic dataset as part of the **Prove It Daily Mission - Day 03**.

---

##  Data Cleaning & Preprocessing
1. **Missing Values**: Imputed missing `Age` values using the median and `Embarked` using the mode. Dropped `Cabin` column due to excessive missing data.
2. **Duplicates**: Identified and removed duplicate rows.
3. **Outliers**: Handled numerical outliers in `Fare` using the Interquartile Range (IQR) method.
4. **Encoding**: Applied One-Hot Encoding to categorical features (`Sex`, `Embarked`).

---

##  Model Training & Evaluation
* **Algorithm:** Logistic Regression
* **Evaluation Metrics:**
  * **Accuracy:** Calculated based on test set split
  * **Precision:** Evaluated model precision
  * **Recall:** Evaluated model recall
