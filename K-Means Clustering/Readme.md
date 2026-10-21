# K-Means Customer Segmentation

This project applies the K-Means clustering algorithm to group mall customers based on their annual income and spending score.

## Algorithm Used

- **K-Means Clustering:** Groups customers into clusters based on similarities in their features.
- **Elbow Method:** Helps determine a suitable number of clusters using Within-Cluster Sum of Squares (WCSS).
- **Silhouette Score:** Evaluates how well customers fit within their assigned clusters.

## Dataset

- **File:** `Mall_Customers.csv`
- **Source:** [Mall Customer Segmentation Data – Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Features used:** Annual Income (k$) and Spending Score (1–100).
- **Purpose:** Identify customer groups with similar income and spending patterns.

Download the dataset, extract the CSV file, and place `Mall_Customers.csv` in the same folder as the notebook.

## Data Analysis and Processing

- Inspect dataset structure, missing values, and statistical summaries.
- Visualize customer data before clustering.
- Use the Elbow Method to examine different cluster counts.
- Apply K-Means with five clusters.
- Display cluster centroids and visualize the resulting groups.

## Evaluation

- Calculate the Silhouette Score to evaluate clustering quality.
- Count the number of customers in each cluster.
- Save the results to `KMeans_Clustered_Customers.csv`.

## Tools and Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook
