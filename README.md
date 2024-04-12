# Spark-learning

This repository contains three Jupyter Notebooks demonstrating different data analysis and machine learning techniques using PySpark:

## SparkSQL: Working with DataFrames and Aggregate Queries on Netflix Movies Dataset
- This notebook provides an introduction to working with PySpark DataFrames and performing aggregate queries using SparkSQL.
- The Netflix movies dataset is used for illustration purposes.
- Topics covered include:
  - Loading data into PySpark DataFrame
  - Basic DataFrame operations (selecting, filtering, grouping)
  - Performing aggregate queries (count, sum, avg)
- Dataset: [Netflix Movies Dataset](https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data)

## RandomForest: Implementation of Random Forest with PySpark on California Housing Dataset
- This notebook demonstrates the implementation of a Random Forest model using PySpark on the California Housing dataset.
- It covers the following steps:
  - Data preprocessing and feature engineering
  - Splitting data into training and testing sets
  - Training a Random Forest model using PySpark MLlib
  - Evaluating model performance using metrics such as RMSE (Root Mean Squared Error)
- Dataset: [California Housing Dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices)

## Clustering: Implementation of KMeans Clustering Using PySpark
- This notebook showcases the implementation of KMeans clustering algorithm using PySpark on Breast Cancer Wisconsin (Diagnostic) Data Set.
- Key steps include:
  - Data preprocessing (scaling features)
  - Training a KMeans clustering model
  - Visualizing the clustering results using PCA (Principal Component Analysis)
- Dataset: [Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

### Usage
To run these notebooks, you need to have Jupyter Notebook installed along with PySpark. You can install PySpark using pip:

```bash
pip install pyspark
```
Once installed, simply clone this repository and run the notebooks in your Jupyter environment.

