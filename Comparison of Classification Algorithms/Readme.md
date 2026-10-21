# Classification Algorithm Comparison

This project compares different Machine Learning classification algorithms using the Iris dataset to predict flower species.

## Algorithms Used

- **Logistic Regression:** Classifies flowers based on their features.
- **Decision Tree:** Uses decision-based rules to classify flowers.
- **Random Forest:** Combines multiple decision trees for classification.
- **Support Vector Machine (SVM):** Finds a decision boundary between classes.
- **K-Nearest Neighbors (KNN):** Classifies flowers based on nearby data points.
- **Naive Bayes:** Uses probability to predict flower classes.

## Dataset

- **Dataset:** Iris dataset
- **Source:** Scikit-learn built-in dataset
- **Features:** Sepal length, sepal width, petal length, and petal width.
- **Target:** Three flower species — Setosa, Versicolor, and Virginica.
- **Download:** No manual download is required. The dataset is loaded using `load_iris()`.

## Data Preprocessing

- Split the dataset into training and testing sets (80:20).
- Apply StandardScaler to standardize the features.
- Train each classification algorithm using the training data.

## Evaluation Metrics

- **Accuracy:** Measures the proportion of correct predictions.
- **Precision:** Measures how many positive predictions are correct.
- **Recall:** Measures how many actual positive cases are identified correctly.

The algorithms are compared using precision, recall, and accuracy to identify the best-performing classifier.

## Tools and Libraries

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook
