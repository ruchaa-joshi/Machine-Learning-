# Regression Model Comparison

This project compares different regression algorithms to predict median house values using the California Housing dataset.

## Algorithms Used

- **Linear Regression:** Models the linear relationship between features and house values.
- **Polynomial Regression:** Captures nonlinear relationships using polynomial features.
- **Decision Tree Regression:** Predicts values using decision-based rules.
- **Random Forest Regression:** Combines multiple decision trees to improve predictions.
- **Support Vector Regression (SVR):** Predicts continuous values using a support vector model.

## Dataset

- **File:** `housing.csv`
- **Source:** [California Housing Prices – Kaggle](https://www.kaggle.com/datasets/camnugent/california-housing-prices)
- **Features:** Housing and geographical information, including income, house age, rooms, population, and ocean proximity.
- **Target:** `median_house_value`

Download the dataset, extract the ZIP file, and place `housing.csv` in the same folder as the notebook.

## Data Preprocessing

- Handle missing numerical values using median imputation.
- Handle missing categorical values using mode imputation.
- Convert categorical data into numerical features using One-Hot Encoding.
- Split the dataset into training and testing sets (80:20).
- Apply feature scaling for Linear Regression, Polynomial Regression, and SVR.

## Evaluation Metrics

- **MAE:** Mean Absolute Error
- **MSE:** Mean Squared Error
- **R² Score:** Measures how well the model explains variation in the target values.

The models are compared using these metrics to identify the best-performing regression algorithm.

## Tools and Libraries

- Python
- Pandas and NumPy
- Scikit-learn
- Jupyter Notebook
