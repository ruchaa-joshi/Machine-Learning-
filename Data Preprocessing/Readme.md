# Data Preprocessing

Data preprocessing prepares raw data for analysis and Machine Learning. The Employee dataset is used to explore data cleaning, missing-value handling, outlier detection, categorical encoding, and feature scaling.

## Key Techniques

- **Data cleaning:** Remove duplicate records and correct inconsistent company names and city spellings.
- **Missing values:** Handle missing Company, Age, Salary, and Place values using mean or mode imputation.
- **Outlier detection:** Identify potential outliers in Age and Salary using the IQR method.
- **Data visualization:** Use scatter plots to examine Age vs Salary and bar charts to compare employees by city.
- **Categorical encoding:** Convert Company, Place, and Gender into numerical features using One-Hot Encoding; demonstrate Label Encoding.
- **Feature scaling:** Apply StandardScaler and MinMaxScaler to numerical features such as Age and Salary.

## Dataset

- **File:** `Employee.csv`
- **Features:** Company, Age, Salary, Place, Country, and Gender.
- **Output:** `Employee_cleaned.csv`, containing the cleaned dataset.

## Typical Workflow

1. Load and inspect the employee dataset.
2. Remove duplicates and correct inconsistent values.
3. Handle missing and invalid values.
4. Check for potential outliers.
5. Visualize and filter employee records.
6. Encode categorical features and scale numerical data.
7. Save the cleaned dataset for further analysis.

## Tools

Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

## Important Note

Fit preprocessing transformations on training data only when building a predictive model, then apply them to validation and test data to avoid data leakage.
