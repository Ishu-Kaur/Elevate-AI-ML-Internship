# Task 5: Decision Trees and Random Forests

## Objective
This task involved building and comparing two powerful tree-based models, a Decision Tree and a Random Forest, for a classification problem using the Heart Disease dataset.

## Key Steps Performed
- **Data Preprocessing:** Loaded the dataset, handled missing values, and converted categorical features into a numerical format using one-hot encoding.
- **Decision Tree Training & Visualization:** A Decision Tree Classifier was trained and visualized using `graphviz` to understand its rule-based structure and demonstrate the concept of overfitting.
- **Model Pruning:** A second, pruned Decision Tree (`max_depth=4`) was trained to control for overfitting, creating a simpler, more generalizable model.
- **Random Forest Training:** A Random Forest, an ensemble of 100 decision trees, was trained, resulting in significantly higher accuracy than the single tree models.
- **Feature Importance & Evaluation:** The feature importances from the Random Forest were visualized to identify the most predictive factors, and the model's performance was robustly validated using 5-fold cross-validation, achieving near-perfect accuracy.

## Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Graphviz