# Customer Churn Analysis

This project focuses on understanding customer churn in a telecommunications company. Using data analysis and visualization techniques, it explores patterns and key factors that influence whether a customer will stay or leave. The goal is to generate insights that can help improve customer retention strategies.

## Overview

Customer churn is a significant issue in the telecom industry. Reducing churn not only increases revenue but also helps build long-term customer relationships. This project analyzes a publicly available dataset to examine how different features such as demographics, service usage, and account information relate to churn behavior.

## Dataset

The dataset includes the following key features:
- Customer ID
- Gender
- Senior citizen status
- Tenure
- Monthly charges
- Total charges
- Churn status

Data cleaning steps included handling missing values, converting data types, and mapping numeric values to more interpretable categories (e.g., converting 0/1 to No/Yes for senior citizen status).

## Tools and Technologies

The analysis was performed using the following tools:
- Python
- Pandas and NumPy for data manipulation
- Matplotlib and Seaborn for data visualization
- Jupyter Notebook for interactive development

## Key Steps in the Project

1. **Data Cleaning**  
   Handled null values, removed inconsistencies, and ensured all data was ready for analysis.

2. **Exploratory Data Analysis**  
   Used visualizations such as count plots, pie charts, and stacked bar charts to explore the relationship between customer features and churn.

3. **Insights**  
   - Approximately 26.5% of customers in the dataset have churned.
   - Senior citizens are more likely to churn compared to younger customers.
   - Gender does not have a strong correlation with churn in this dataset.

## Visualizations

The project includes several visualizations that help interpret the data, including:
- Count plots by gender and senior citizen status
- Churn distribution visualized using pie and bar charts
- Stacked bar charts with percentage labels for clearer comparison

## Summary

This analysis provides a foundational understanding of what drives customer churn in the telecom sector. The insights can be used by marketing and support teams to target high-risk customers and improve retention strategies.

## PDF Report

A summarized report of the key insights and findings from this analysis is available in the file `Churn_Analysis_Insights.pdf`.

## Future Improvements

- Extend the analysis to include service types, payment methods, and contract duration.
- Build a predictive machine learning model to classify churn.
- Create an interactive dashboard for real-time monitoring of churn metrics.

## About the Author

RAJEEB LOCHAN BEHERA 
Final Year B.Tech Student in Electronics and Telecommunication Engineering  
Enthusiastic about data analysis, storytelling with data, and solving real-world problems using Python.

