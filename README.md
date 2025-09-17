Pizza Sales Data Analysis

This notebook contains an analysis of a pizza sales dataset to gain insights into various aspects of the business, including delivery performance, customer behavior, and factors influencing delivery duration.

Analysis Performed
The analysis covered the following key areas:

Data Loading and Cleaning:

Loading the dataset from an Excel file.
Handling missing values in numerical and categorical columns.
Converting date/time columns to appropriate formats.
Exploratory Data Analysis (EDA):

Summarizing descriptive statistics for numerical features.
Analyzing the distribution and frequency of various features (e.g., Pizza Size, Traffic Level).
Grouping data to understand performance metrics by categories like Restaurant and Location.
Creating visualizations to illustrate trends and patterns, including:
Histograms of key numerical variables.
Bar plots of average delivery duration by location and pizza size popularity.
Line plot of average delivery duration trends by month.
Heatmap of average delivery duration by traffic level.
Correlation Analysis:

Exploring the linear relationships between numerical variables using a correlation matrix.
Predictive Modeling:

Building and evaluating regression models (Random Forest, Linear Regression, Decision Tree) to predict 'Delivery Duration (min)'.
Identifying the best performing model based on evaluation metrics (MAE, MSE, RMSE, R-squared).
Using the best model to make predictions and visualizing actual vs. predicted values.
Customer Segmentation:

Performing clustering analysis (K-Means) to identify distinct customer segments based on their order patterns.
Analyzing the characteristics of each identified cluster.
Key Findings
The analysis revealed insights into factors affecting delivery duration, such as distance, traffic, and estimated time.
The Random Forest Regressor model demonstrated high accuracy in predicting delivery duration.
Distinct customer segments were identified based on their ordering preferences and patterns, which can inform targeted marketing strategies.
How to Use
This notebook can be run sequentially to reproduce the analysis. Ensure you have the required libraries installed (pandas, numpy, matplotlib, seaborn, scikit-learn).

Dataset
The analysis was performed on the "Enhanced_pizza_sell_data_2024-25.xlsx" dataset
