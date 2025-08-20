# WHO-COVID-19-global-daily-data-analysis-project

# COVID-19 Data Analysis 🦠

This repository contains a comprehensive Exploratory Data Analysis (EDA) of a COVID-19 dataset. The notebook investigates the spread and impact of the virus over time across different countries and WHO regions.

## Project Overview

The goal of this project is to understand the key characteristics of the COVID-19 pandemic data through visualizations and statistical analysis. The notebook covers data cleaning, feature engineering, and a detailed examination of both univariate and bivariate relationships within the dataset.

## Key Features

* **Data Cleaning**: Handles missing values and addresses data anomalies, including negative values which represent corrections in reporting.
* **Feature Engineering**: Extracts temporal features from the date column and derives new metrics like the **Case Fatality Rate** to provide deeper insights.
* **Univariate Analysis**: Explores the distribution and summary statistics of each individual variable using **histograms**, **box plots**, and **bar charts**.
* **Bivariate Analysis**: Investigates the relationships between pairs of variables using **scatter plots**, **joint plots**, and **box plots** to uncover correlations and trends.
* **Interactive Visualizations**: Uses libraries like Matplotlib and Seaborn to create clear and informative plots that are easy to interpret.

## Repository Contents

* `covid_analysis.ipynb`: The main Jupyter Notebook containing all the code and analysis.
* `README.md`: This file, providing an overview of the project.
* `WHO-COVID-19-global-daily-data.csv`: This file, dataset used.

## Requirements

* The project uses common Python data science libraries. You can install them using pip:

* pip install pandas matplotlib seaborn numpy plotly

## Conclusions

The analysis reveals the highly skewed nature of COVID-19 reporting, with a few major outbreaks driving the global numbers. The negative values, representing data corrections, were identified and understood. The project successfully visualizes the spread of the virus and highlights key differences in its impact across various countries and regions.
