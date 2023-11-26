# Market Basket Analysis with Apriori Algorithm

## Overview
This repository contains a Python script for performing Exploratory Data Analysis and Market Basket Analysis using the Apriori algorithm. The analysis is applied to a grocery sales dataset to  extract valuable insights from transaction data and discover associations between different products for the purpose of business optimization.


## Code Structure
* Data Loading and Cleaning:
  - Load the grocery sales data and perform initial data cleaning.
  - Convert 'Member_number' to a string and 'Date' to datetime format.

* Exploratory Data Analysis:
  - Identify trends and patterns in customer purchases.

* Unique Transactions:
  - Create a 'uniqueTransaction' column to group items purchased per customer per day.

* Cross-Tabulation (Basket Creation):
  - Create a cross-tabulation ('basket') to represent the frequency of items in each unique transaction.
  - Create a binary-encoded DataFrame ('apriori_df').

* Apriori Algorithm and Association Rules:
  - Apply the Apriori algorithm to generate frequent itemsets.
  - Use association rules, focusing on Zhang's metric for evaluation.

* Heatmap Visualization:
  - Visualize product associations using a heatmap.
  - Interpret the heatmap to understand frequent itemsets.

* Positive Association Visualization:
  - Explore pairs with positive Zhang's metric to highlight positive associations.


## Dataset
This analysis was done on  a grocery sales dataset, containing transaction data on items purchased by customers. The csv file - Market Basket Analysis - Groceries_dataset - is included in this repository.


## Analysis
The Jupyter Notebook file [Market_Basket_Analysis.ipynb] (Market_Basket_Analysis.ipynb) contains a detailed analysis, including data processing steps, Exploratory Data Analysis, Market Basket Analysis using the Apriori algorithm, visualizations, and insights and recomendations.


## How to use
1. Clone the repository.
2. Open the Jupyter Notebook [Market_Basket_Analysis.ipynb] (./main/Market_Basket_Analysis.ipynb) to view the analysis.
3. Customize the analysis for your own dataset if needed.


## Dependencies
The analysis is done using Python and popular libraries like pandas, matplotlib, seaborn, and mlxtend. Make sure to install these dependencies using the following:

pip install pandas matplotlib seaborn mlxtend
