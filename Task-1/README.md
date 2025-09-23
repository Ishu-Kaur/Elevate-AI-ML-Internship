# Task 1: Data Cleaning and Preprocessing

## Objective
This task focuses on the fundamental steps of cleaning and preparing raw data to make it suitable for machine learning models. The Titanic dataset was used for this exercise.

## Key Steps Performed
- **Handled Missing Values:** Filled missing `Age` and `Embarked` data using median and mode imputation.
- **Data Transformation:** Converted categorical features (like `Sex` and `Embarked`) into numerical format using one-hot encoding.
- **Feature Scaling:** Standardized numerical features (`Age`, `Fare`, etc.) to bring them onto a common scale.
- **Outlier Removal:** Identified and removed significant outliers from the `Fare` column using the IQR method.

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn