# Support Vector Machine (SVM)

Support Vector Machine (SVM) is a supervised Machine Learning algorithm used for classification and regression. It classifies data by finding an optimal decision boundary that separates different classes.

## Key Concepts

- **Data Preparation:** Load and inspect the dataset, check missing values, and separate features from the target.
- **Train-Test Split:** Divide data into training and testing sets.
- **Feature Scaling:** Standardize numerical features using StandardScaler.
- **SVM Classification:** Train an SVM classifier using the RBF kernel.
- **Model Evaluation:** Evaluate predictions using accuracy, confusion matrix, precision, recall, and F1-score.
- **Kernel Comparison:** Compare linear, polynomial, RBF, and sigmoid kernels.
- **Parameter Tuning:** Examine how different values of `C` affect classification performance.
- **New Predictions:** Predict the species of a new flower sample.

## Dataset

- **File:** `iris.csv`
- **Features:** Sepal length, sepal width, petal length, and petal width.
- **Target:** `species`, representing the flower species.
- **Purpose:** Classify Iris flowers based on their measurements.

## Typical Workflow

1. Load and explore the Iris dataset.
2. Separate input features and target labels.
3. Split the data into training and testing sets.
4. Standardize the features.
5. Train the SVM classifier.
6. Evaluate model performance using classification metrics.
7. Compare kernels and different values of `C`.
8. Predict the species of a new flower.

## Tools

Python, Pandas, NumPy, Matplotlib, and Scikit-learn.

## Conclusion

SVM can classify Iris flower species using their measurements. Feature scaling, kernel selection, and parameter tuning help understand and improve classification performance.

