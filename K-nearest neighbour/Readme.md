# K-Nearest Neighbors (KNN)

K-Nearest Neighbors (KNN) is a supervised Machine Learning algorithm used for classification and regression. It predicts the class of a data point based on the classes of its nearest neighbors.

## Key Concepts

- **Data Preparation:** Load the dataset and separate input features from target labels.
- **Train-Test Split:** Divide the dataset into training and testing sets.
- **Feature Scaling:** Standardize numerical features using StandardScaler.
- **KNN Classification:** Train a KNN classifier using `n_neighbors=5`.
- **Model Evaluation:** Measure performance using accuracy, precision, recall, F1-score, and a classification report.

## Dataset

- **File:** `iris.csv`
- **Features:** Sepal length, sepal width, petal length, and petal width.
- **Target:** `species`, representing the Iris flower species.
- **Purpose:** Classify flowers based on their measurements.

## Typical Workflow

1. Load the Iris dataset.
2. Separate features and target labels.
3. Split the data into training and testing sets.
4. Standardize the numerical features.
5. Train the KNN classifier with five neighbors.
6. Predict flower species for the test data.
7. Evaluate classification performance.

## Tools

Python, Pandas, NumPy, and Scikit-learn.

## Conclusion

KNN classifies data based on the nearest training samples. Feature scaling is important because KNN relies on distances between data points, and the choice of neighbor count can affect classification performance.

