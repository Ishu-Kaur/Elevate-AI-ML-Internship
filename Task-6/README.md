# Task 6: K-Nearest Neighbors (KNN) Classification

## Objective
This task focused on understanding and implementing the K-Nearest Neighbors (KNN) algorithm for a multi-class classification problem using the classic Iris dataset.

## Key Steps Performed
1.  **Data and Feature Selection:** Loaded the Iris dataset from Scikit-learn and selected the first two features (sepal length and width) to allow for 2D visualization.
2.  **Feature Scaling:** Standardized the features using `StandardScaler`, a critical step for distance-based algorithms like KNN.
3.  **Optimal K Selection:** Experimented with a range of K values and plotted the error rate to identify the optimal number of neighbors, which minimizes the model's error on the test set.
4.  **Model Training & Evaluation:** Trained the final `KNeighborsClassifier` with the best K value and evaluated its performance using accuracy and a confusion matrix.
5.  **Decision Boundary Visualization:** Plotted the model's decision boundaries to visually understand how the KNN algorithm separates the feature space into the three different Iris species.

## Tools Used
- Python, Pandas
- Scikit-learn (`KNeighborsClassifier`, `StandardScaler`)
- Matplotlib, Seaborn