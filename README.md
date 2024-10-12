# AB Testing and Marketing Campaign Analysis

## Overview
This repository contains a Jupyter notebook that performs an analysis of marketing campaigns using **AB testing** and **econometric techniques**. The goal is to investigate the relationship between marketing spend on ads (such as Facebook ads) and the resulting conversions.

## Key Features
- **Data Loading and Cleaning**: The notebook starts by importing the necessary libraries and loading the campaign data. It also demonstrates preprocessing steps to clean the data.
  
- **Exploratory Data Analysis (EDA)**: 
  - Descriptive statistics of marketing spend and conversions.
  - Visualizations of the distribution and trends over time.

- **AB Testing**:
  - An AB test is conducted to measure the effectiveness of different campaign strategies.
  - Hypothesis testing is used to determine if there is a statistically significant difference in the performance of ads.

- **Econometric Analysis**:
  - **Cointegration Tests**: The notebook runs cointegration tests to assess whether there is a long-term relationship between advertising spend (e.g., Cost per Facebook Ad) and the number of conversions.
  - The results of these tests provide insight into the optimal allocation of marketing budgets.

## Requirements
The notebook requires the following libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `statsmodels`
- `scipy`
