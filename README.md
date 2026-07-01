# Wholesale Customers Clustering Analysis

This project demonstrates the application of unsupervised machine learning algorithms to segment wholesale customers based on their annual spending across various product categories.

## Dataset
The project utilizes the [Wholesale Customers Dataset](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers), which includes annual spending data on categories like Fresh food, Milk, Grocery, Frozen goods, Detergents_Paper, and Delicassen.

## Features
*   **Data Preprocessing:** Cleaning and scaling numerical data using `StandardScaler` to ensure optimal model performance.
*   **Clustering Models:**
    *   **K-Means:** Grouping customers into 5 distinct clusters to analyze spending behavior.
    *   **DBSCAN:** Exploring density-based clustering to identify outliers and dense regions.
*   **Visualization:** Using `seaborn` and `matplotlib` to visualize cluster relationships (e.g., Grocery vs. Fresh spending).
*   **Evaluation:** Calculating the **Silhouette Score** to evaluate the quality of the clustering.

## Prerequisites
*   Python 3.x
*   pandas
*   numpy
*   scikit-learn
*   seaborn
*   matplotlib

## Installation
Clone this repository and install the dependencies:
```bash
pip install pandas numpy scikit-learn seaborn matplotlib
Usage
Load the dataset within the notebook.

Run the preprocessing steps to scale the data.

Execute the K-Means and DBSCAN cells to generate clusters.

Review the visual plots to interpret customer segments.

License
This project is open-source and intended for educational purposes.
