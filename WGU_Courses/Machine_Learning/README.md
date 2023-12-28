# Customer Segmentation and Targeted Marketing

## Overview
This project focuses on analyzing demographic data of the general population in Germany and identifying clusters within it. The ultimate goal is to understand how these demographic clusters relate to the customer base of a mail-order sales company. The project involves data cleaning, feature engineering, dimensionality reduction, and k-means clustering.

## Key Steps

### 1. Data Preprocessing and Feature Engineering
- Cleaned and assessed demographic data, handling missing values and irrelevant columns.
- Engineered features using a custom function (`clean_data`) for preprocessing.

### 2. Feature Scaling and Principal Component Analysis (PCA)
- Standardized and scaled features for PCA using `StandardScaler`.
- Applied PCA to reduce dimensionality while retaining significant variance.
- Interpreted principal components to understand feature associations.

### 3. K-Means Clustering
- Applied k-means clustering to identify natural groupings in the data.
- Tested various cluster counts to find an optimal number based on average within-cluster distances.
- Selected a final number of clusters for further analysis.

### 4. Applying Clustering to Customer Data
- Applied the same preprocessing and feature engineering steps to the customer demographics.
- Used existing sklearn objects from the general population data for feature scaling, PCA, and clustering on customer data.

### 5. Comparing Customer Data to Demographics Data
- Compared the proportions of persons in each cluster for the general population and customer data.
- Identified overrepresented and underrepresented clusters.
- Inferred characteristics of these clusters based on principal components and data dictionary.

## Findings
- Discovered clusters representing both overrepresented and underrepresented customer populations.
- Interpreted characteristics of these clusters to provide insights for targeted marketing strategies.

For detailed discussions and findings, refer to the notebook.

## Dependencies
- Python 3.x
- Libraries: pandas, numpy, sklearn, matplotlib, seaborn


