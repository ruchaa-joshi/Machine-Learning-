# Principal Component Analysis (PCA)

Principal Component Analysis (PCA) is a dimensionality reduction technique used to reduce the number of features in a dataset while retaining as much information as possible. This concept demonstrates PCA with feature scaling and Logistic Regression classification.

## Key Techniques

- **Dataset creation:** Create a sample dataset containing Height, Weight, Age, and Gender.
- **Feature and target separation:** Separate input features from the target variable.
- **Standardization:** Scale numerical features using StandardScaler.
- **Dimensionality reduction:** Apply PCA to transform three numerical features into two principal components.
- **Variance analysis:** Examine the explained variance ratio to understand how much information the principal components retain.
- **Classification:** Train a Logistic Regression model using the transformed features.
- **Model evaluation:** Compare actual and predicted labels using a confusion matrix.
- **Visualization:** Compare the first two standardized features with the two principal components.

## Dataset

- **Source:** Sample dataset created using Python.
- **Features:** Height, Weight, and Age.
- **Target:** Gender, represented as `1` for Male and `0` for Female.
- **Purpose:** Demonstrate dimensionality reduction and classification.

## Typical Workflow

1. Create the dataset and separate features from the target.
2. Standardize the numerical features.
3. Apply PCA to reduce dimensionality.
4. Analyze the explained variance.
5. Split the data into training and testing sets.
6. Train a Logistic Regression model and make predictions.
7. Evaluate the predictions using a confusion matrix.
8. Visualize the data before and after PCA.

## Tools

Python, NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn.

## Important Note

For a reliable evaluation, fit the scaler and PCA using only the training data, then transform the test data using those fitted objects. This avoids data leakage. The small sample dataset is intended for learning and does not establish real-world classification performance.

## Conclusion

PCA reduces the dimensionality of numerical data while preserving important patterns. Combined with feature scaling, classification, and visualization, it helps demonstrate how dimensionality reduction can support machine learning workflows.
