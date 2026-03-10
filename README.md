Walmart Sales Data Analysis (EDA)
Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Walmart Sales dataset to understand sales patterns, identify trends, and analyze factors that may influence weekly sales across different stores.

The goal of this analysis is to extract meaningful insights from the dataset using Python-based data analysis and visualization techniques.

Dataset Description

The dataset contains weekly sales data for 45 Walmart stores, along with several factors that may influence sales performance.

Features in the dataset

Store – Store number

Date – Week of sales

Weekly_Sales – Weekly sales amount

Holiday_Flag – Indicates whether the week includes a holiday (1 = Holiday, 0 = Non-Holiday)

Temperature – Temperature during the week

Fuel_Price – Cost of fuel in the region

CPI – Consumer Price Index

Unemployment – Unemployment rate

Tools and Technologies Used

Python

Pandas – Data manipulation and analysis

NumPy – Numerical computations

Matplotlib – Data visualization

Seaborn – Statistical data visualization

Jupyter Notebook

Exploratory Data Analysis Steps
1. Data Loading

The dataset was loaded using Pandas to inspect its structure and content.

2. Data Cleaning

Converted column names to lowercase

Checked for missing values

Verified data types

3. Data Type Conversion

The date column was converted to datetime format to enable time-based analysis.

4. Descriptive Statistics

Basic statistical summaries were generated to understand the distribution of numerical variables.

5. Univariate Analysis

Individual variables were analyzed using:

Histograms

Boxplots

This helped understand distributions and detect potential outliers.

6. Bivariate Analysis

Relationships between variables were explored using scatter plots and boxplots to examine how different factors influence weekly sales.

7. Correlation Analysis

A correlation heatmap was created to visualize relationships between numerical features.

8. Time Series Analysis

Weekly sales were analyzed over time to identify trends and seasonal patterns.

9. Holiday Impact Analysis

Sales during holiday weeks were compared with non-holiday weeks to evaluate the impact of seasonal events on revenue.


Key Insights

Weekly sales vary significantly across different Walmart stores.

Holiday weeks tend to generate higher sales compared to non-holiday weeks.

Economic indicators such as fuel price and unemployment rate show weak correlation with weekly sales.

Time series analysis reveals periodic spikes in sales during major retail events.

Visualizations Included

The project includes several visualizations such as:

Sales distribution plots

Scatter plots between economic indicators and sales

Correlation heatmap

Sales trends over time

Holiday vs non-holiday sales comparison

