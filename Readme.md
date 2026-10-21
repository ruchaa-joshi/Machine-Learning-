# Machine Learning Concepts

This repository contains implementations of fundamental Machine Learning concepts and algorithms using Python. It covers data preprocessing, exploratory data analysis, regression, classification, dimensionality reduction, clustering, and artificial neural networks.

## Topics Covered

### 1. Data Preprocessing
Learn how to prepare raw data for Machine Learning by handling missing values, removing duplicate records, detecting outliers, encoding categorical variables, and scaling numerical features.

- **Dataset:** `Employee.csv`
- **Tools:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

### 2. Exploratory Data Analysis (EDA)
Explore datasets using statistical summaries, missing-value analysis, and visualizations to identify patterns, relationships, and trends.

- **Dataset:** `titanic.csv`
- **Tools:** Pandas, NumPy, Matplotlib, Seaborn

### 3. Principal Component Analysis (PCA)
Understand dimensionality reduction by transforming features into a smaller set of principal components while retaining important information.

- **Dataset:** Synthetic sample data
- **Tools:** NumPy, Pandas, Scikit-learn, Matplotlib

### 4. Linear and Logistic Regression
Explore regression and classification techniques. Linear Regression predicts continuous values, while Logistic Regression predicts class labels.

- **Dataset:** Synthetic data generated using NumPy
- **Tools:** NumPy, Pandas, Scikit-learn, Matplotlib

### 5. Support Vector Machine (SVM)
Implement SVM for classification and explore how different kernels can separate data points into classes.

- **Dataset:** `iris.csv`
- **Tools:** Pandas, Scikit-learn, Matplotlib

### 6. K-Nearest Neighbors (KNN)
Classify data points based on the labels of their nearest neighbors and evaluate the model's performance.

- **Dataset:** `iris.csv`
- **Tools:** Pandas, Scikit-learn

### 7. Regression Model Comparison
Compare multiple regression algorithms to predict median house values and evaluate their performance using different metrics.

- **Dataset:** `housing.csv` — California Housing Prices dataset
- **Algorithms:** Linear Regression, Polynomial Regression, Decision Tree Regression, Random Forest Regression, and Support Vector Regression (SVR)
- **Tools:** Pandas, NumPy, Scikit-learn

### 8. Classification Algorithm Comparison
Compare multiple classification algorithms for predicting flower species using the Iris dataset.

- **Dataset:** Iris dataset provided by Scikit-learn
- **Algorithms:** Logistic Regression, Decision Tree, Random Forest, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), and Naive Bayes
- **Evaluation Metrics:** Accuracy, Precision, Recall
- **Tools:** Pandas, Scikit-learn

### 9. K-Means Clustering
Apply unsupervised learning to segment mall customers based on annual income and spending score.

- **Dataset:** `Mall_Customers.csv`
- **Techniques:** Elbow Method, cluster visualization, centroid analysis, and Silhouette Score
- **Output:** `KMeans_Clustered_Customers.csv`
- **Tools:** NumPy, Pandas, Matplotlib, Scikit-learn

### 10. Single-Layer Artificial Neural Network (ANN)
Build a simple neural network from scratch for binary classification using sigmoid activation, forward propagation, and gradient descent.

- **Dataset:** Manually created sample data using NumPy
- **Concepts:** Weights, bias, learning rate, epochs, prediction, and accuracy
- **Tools:** NumPy, Matplotlib

## Datasets

Some implementations use built-in datasets, while others require CSV files.

| Dataset | Used For |
|---|---|
| `Employee.csv` | Data Preprocessing |
| `titanic.csv` | Exploratory Data Analysis |
| `iris.csv` | SVM and KNN |
| `housing.csv` | Regression Model Comparison |
| `Mall_Customers.csv` | K-Means Clustering |
| Synthetic sample data | PCA, Regression, and ANN |
| Built-in Iris dataset | Classification Algorithm Comparison |

**Note:** Download the required CSV datasets and place them in the same folder as their respective notebooks. The built-in Iris dataset and synthetic sample data do not require manual downloads.

## Technologies Used

- **Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:**
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn

## Installation

Install the required libraries using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

## General Workflow

1. Load or create the dataset.
2. Explore the data and understand its features.
3. Preprocess the data when required.
4. Split data into training and testing sets for supervised learning.
5. Train the appropriate Machine Learning algorithm.
6. Evaluate model performance using suitable metrics.
7. Visualize results where applicable.

## Learning Objectives

- Understand fundamental Machine Learning concepts.
- Perform data cleaning and exploratory analysis.
- Implement supervised and unsupervised learning algorithms.
- Compare models using appropriate evaluation metrics.
- Visualize data, predictions, and clustering results.
- Practice implementing algorithms using Python and Scikit-learn.

## Repository Purpose

This repository serves as a learning resource for understanding and implementing fundamental Machine Learning techniques through code examples and datasets.
