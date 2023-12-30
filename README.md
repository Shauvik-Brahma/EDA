# Exploratory Data Analysis (EDA)

# N.B - 

## About
Exploratory Data Analysis (EDA) is a critical step in data analysis to understand the dataset, identify patterns, and derive initial insights before modeling.

## Content
- Problem Statement
- Load Libraries
- Data Descriptions
- Data Cleaning
- Exploratory Data Analysis
- Summary

## Data Preparation
- **Pandas Functions:**
  -     `read_csv()`: Loads data from a CSV file into a Pandas DataFrame.
  -     `head()`: Displays the first few rows of the DataFrame to check the data.
  -     `info()`: Provides a summary of the DataFrame, including column data types and missing values.
-      `describe()`: Generates descriptive statistics of the DataFrame's numerical columns.
-     `isnull()`: Checks for missing or null values in the DataFrame.
-     `fillna()`: Fills missing values in the DataFrame with specified data.
 -     `dropna()`: Drops rows or columns with missing values from the DataFrame.
-     `astype()`: Converts the data type of a column to a specified type.
-     `apply()`: Applies a function along an axis of the DataFrame.
  -     `corr()`: Computes pairwise correlation of columns using Pearson, Kendall, or Spearman method.
  
- **Rank Correlation by Scipy:**
  - Utilizes `scipy.stats.spearmanr()` to calculate the correlation coefficient for ranked data.

## Exploration
- **Libraries:**
  - **Matplotlib:** Offers basic plotting functions for creating visualizations.
  - **Seaborn:** Provides enhanced visualizations and statistical graphics.
  - **Plotly:** Allows interactive and web-based visualizations.

## Projects
- World Bank Data Analysis
- Amazon Customer Behavior
- Climate Change Analysis


