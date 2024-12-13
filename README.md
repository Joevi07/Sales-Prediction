# Sales-Prediction
### Overview
This project involves clustering customer shopping data using machine learning techniques. It focuses on exploratory data analysis, data preprocessing, and applying clustering algorithms like K-Means and DBSCAN to identify patterns in shopping behavior.
### Features
#### Data Preprocessing:
Handling missing values, encoding categorical variables, and feature scaling.
#### Exploratory Data Analysis (EDA):
* Gender distribution
* Age distribution
* Purchase category count
* Payment method breakdown
#### Clustering Models:
* K-Means: Includes elbow method for optimal cluster selection.
* DBSCAN: Evaluated using Silhouette Scores.
#### Visualization: 
Scatter plots, histograms, and pie charts for better data interpretation.
### Dataset
The dataset contains customer transaction records with the following features:

<b>Invoice Number:</b>Unique identifier for each transaction.  
<b> Customer ID:</b> Unique identifier for each customer.  
<b> Gender:</b> Male or Female.  
<b> Age:</b> Customer age.  
<b> Category:</b> Product category.  
<b> Quantity:</b> Number of products purchased.  
<b> Price:</b> Total price of the transaction.  
<b> Payment Method:</b> Payment method used (e.g., Credit Card, Cash).  
<b> Invoice Date:</b> Date of the transaction.  
<b> Shopping Mall:</b> Location of the purchase.  
### Dependencies
The following dependencies are required for this project:
* Python (3.x)
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
### Results  

Key outcomes of the project:  
<b>Optimal Clusters (K-Means):</b> Determined using the Elbow method.  
<b>Cluster Analysis:</b> Identified distinct clusters based on spending patterns, gender, and product categories.  
<b>Silhouette Scores:</b>
* K-Means: 0.73  
* DBSCAN: 0.67  


