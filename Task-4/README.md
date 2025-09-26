# Task 4: Classification with Logistic Regression

## Objective
This task involved building a binary classification model using Logistic Regression to predict whether a breast cancer tumor is malignant or benign based on the Wisconsin Breast Cancer dataset.

## Key Steps Performed
- **Data Loading and Preparation:** Loaded the dataset directly from Scikit-learn and converted it into a Pandas DataFrame.
- **Feature Scaling and Data Splitting:** Standardized all numerical features using `StandardScaler` to ensure optimal model performance and split the data into training and testing sets.
- **Model Training:** Fitted a `LogisticRegression` model from Scikit-learn on the standardized training data.
- **Model Evaluation:** Evaluated the classifier using a comprehensive set of metrics including Accuracy, Precision, Recall, ROC-AUC, and a visual Confusion Matrix.
- **Model Interpretation:** Visualized and explained the role of the sigmoid function and plotted the ROC curve to understand the trade-offs at different classification thresholds.

## Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib