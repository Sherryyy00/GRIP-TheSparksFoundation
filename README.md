# GRIP-TheSparksFoundation
Author: Muhammad Sheryar Adil


Data Science


GRIP October'23


# Data Analysis Project

This repository contains three tasks involving data analysis and machine learning using Python. The tasks are:

1. **Linear Regression Analysis on Student Scores Data**
2. **K-Means Clustering on Iris Dataset**
3. **Exploratory Data Analysis on Retail Dataset**

## Task 1: Linear Regression Analysis on Student Scores Data

### Objective
The objective of this task is to predict the scores of students based on the number of hours they studied using linear regression.

### Steps
1. **Import Libraries**:
   - Import necessary libraries such as pandas, numpy, matplotlib, and sklearn.
2. **Load Data**:
   - Load the dataset from a URL and display the first 15 rows.
3. **Data Visualization**:
   - Plot the data to visualize the relationship between hours studied and scores obtained.
4. **Data Preparation**:
   - Split the data into features (hours) and target (scores).
5. **Train-Test Split**:
   - Split the data into training and testing sets.
6. **Model Training**:
   - Train a linear regression model on the training data.
7. **Model Visualization**:
   - Plot the regression line with the data points.
8. **Prediction**:
   - Make predictions on the test data.
9. **Evaluation**:
   - Compare the actual and predicted scores.
   - Calculate and display the Mean Absolute Error (MAE).

### Output
- A scatter plot of hours vs. scores.
- A line plot of the regression line.
- A comparison of actual and predicted scores.
- Mean Absolute Error (MAE) value.

### Libraries Used
- pandas
- numpy
- matplotlib
- sklearn

## Task 2: K-Means Clustering on Iris Dataset

### Objective
The objective of this task is to perform clustering on the Iris dataset to identify different species of Iris flowers.

### Steps
1. **Import Libraries**:
   - Import necessary libraries such as pandas, numpy, matplotlib, and sklearn.
2. **Load Data**:
   - Load the Iris dataset and display the first 5 rows.
3. **Data Preparation**:
   - Extract the feature variables from the dataset.
4. **Elbow Method**:
   - Use the Elbow Method to determine the optimal number of clusters.
5. **Model Training**:
   - Train a K-Means clustering model with the optimal number of clusters.
6. **Cluster Visualization**:
   - Visualize the clusters and their centroids.

### Output
- A plot showing the Elbow Method to determine the optimal number of clusters.
- A scatter plot visualizing the clusters and centroids.

### Libraries Used
- pandas
- numpy
- matplotlib
- sklearn

## Exploratory Data Analysis - Retail Dataset

### Objective
This project involves performing an exploratory data analysis (EDA) on a retail dataset named 'SampleSuperstore.' The analysis aims to understand the business's overall performance, identify profitable and loss-making segments, and offer insights for strategic decision-making.

### Steps
1. **Import Libraries**:
   - Import necessary libraries such as pandas, numpy, matplotlib, and seaborn.
2. **Load Data**:
   - Load the dataset and display the first 5 rows.
3. **Data Overview**:
   - Display summary statistics and check for missing values.
4. **Data Cleaning**:
   - Remove duplicate entries from the dataset.
5. **Overall Profit/Loss Analysis**:
   - Calculate and display the overall profit/loss of the business.
6. **Category-wise Analysis**:
   - Analyze profit/loss and sales by different categories.
7. **Region-wise Analysis**:
   - Analyze profit/loss and sales by different regions.
8. **Sub-Category Analysis**:
   - Analyze profit/loss by different sub-categories.
9. **Discount Analysis**:
   - Analyze the impact of discount on profit/loss.
10. **Shipping Mode Analysis**:
    - Analyze sales and profit by different shipping modes.
11. **Segment Analysis**:
    - Analyze sales and profit by different customer segments.
12. **State-wise Analysis**:
    - Analyze sales and profit by different states.
13. **Recommendations**:
    - Provide recommendations based on the analysis.

## Features of the Analysis

1. **Overall Profit/Loss**: Calculates the total profit or loss for the business.
2. **Profit/Loss by Category**: Analyzes profit and loss across different product categories.
3. **Profit/Loss by Region**: Breaks down profit and loss by geographical region.
4. **Profit/Loss by Sub-Category**: Examines profit and loss at the sub-category level.
5. **Sales by Category**: Visualizes sales distribution across categories.
6. **Sales by Region**: Provides a regional sales breakdown.
7. **Profit/Loss by Discount**: Investigates the impact of discounts on profit and loss.
8. **Profit & Sales by Ship Mode**: Analyzes profit and sales based on different shipping methods.
9. **Sales & Profit by Segment**: Studies the profit and sales across customer segments.
10. **Sales & Profit by State**: Looks at profit and sales performance at the state level.

## Data Analysis

The analysis provides several key insights:

- **Overall Profit/Loss**: The business has a total profit of $286,241.42.
- **Category and Region Performance**: Some categories and regions perform better than others. For instance, office supplies generally show positive profits, while furniture and technology vary.
- **Impact of Discounts**: Higher discounts generally lead to lower profits, indicating the need for optimized discount strategies.
- **Shipping and Segmentation Insights**: The shipping method and customer segment analysis suggest opportunities to optimize shipping costs and target profitable customer segments.

These insights can be used to make data-driven decisions to improve business profitability and efficiency.


## Conclusion
This repository provides a comprehensive analysis of different datasets using linear regression, clustering, and exploratory data analysis techniques. The insights and visualizations derived from these tasks can help in making informed business decisions.

