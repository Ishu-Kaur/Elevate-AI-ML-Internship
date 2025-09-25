# Task 3: Linear Regression

## Objective
This task involved implementing and understanding simple & multiple linear regression by building a model to predict house prices from the Housing dataset.

## Key Steps Performed
- **Data Preprocessing:** Loaded the dataset, converted all categorical features (binary 'yes'/'no' and multi-level 'furnishingstatus') into a numerical format suitable for modeling.
- **Train-Test Split:** Divided the data into an 80% training set and a 20% testing set to ensure an unbiased evaluation of the model's performance on unseen data.
- **Model Training:** Initialized and fitted a `LinearRegression` model from the Scikit-learn library using the training data.
- **Model Evaluation:** Assessed the model's predictive accuracy on the test set using standard regression metrics, including Mean Absolute Error (MAE), Mean Squared Error (MSE), and the R-squared (R²) score.
- **Interpretation & Visualization:** Plotted the model's predictions against the actual values to visually gauge performance and interpreted the model's coefficients to understand the influence of each feature on house price prediction.

## Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib