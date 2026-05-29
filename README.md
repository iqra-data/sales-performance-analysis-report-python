# Sales Performance Analysis Using Python

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1m2rSdenEyubWwL5mMUMbQ4ZHQi5IAb59)

## Project Overview

This project analyses six months of sales data from One Time Sales and Marketing Ltd. using Python. The analysis focuses on salesperson performance, customer purchasing behaviour, shipping methods, sales trends, and the relationship between sales value and order priority.

## Objectives

- Evaluate salesperson performance
- Analyse monthly and weekly sales trends
- Examine customer purchasing behaviour
- Assess shipping mode utilisation
- Investigate the relationship between sales value and order priority
- Apply data preprocessing and feature engineering techniques

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- ydata-profiling

## Data Preparation

The dataset was prepared using:

- Header correction
- Data type validation
- Missing value verification
- Duplicate detection
- Outlier removal using the IQR method
- Text standardisation
- Feature engineering
- Automated data profiling

## Feature Engineering

Additional variables were created, including:

- priority_score
- priority_values
- customer_avg_sales
- customer_total_spend
- salesperson_total_sales
- high_value_order
- high_value
- log_value
- days_since_last_order
- week
- month_name

## Exploratory Data Analysis (EDA)

The analysis included:

- Frequency distribution analysis
- Salesperson performance analysis
- Customer behaviour analysis
- Shipping mode analysis
- Monthly revenue analysis
- Weekly revenue analysis
- Correlation analysis
- Heatmaps, boxplots, scatter plots, bar charts, and line charts

## Key Findings

- Pryia generated the highest total sales revenue.
- Kelly handled the highest number of unique customers.
- Plane was the most frequently used shipping method.
- August recorded the highest monthly sales revenue.
- June recorded the lowest monthly sales revenue.
- A small number of customers contributed a significant proportion of total sales.
- The relationship between sales value and order priority was weak (correlation = 0.069).

## Repository Structure

```text
dataset/     -> Sales dataset
images/      -> Visualisations
notebook/    -> Python notebook
report/      -> Final report
