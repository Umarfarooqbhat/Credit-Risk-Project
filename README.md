# Credit Risk Analysis Project

## Overview
This project focuses on analyzing credit risk using historical loan application data. The goal is to identify patterns that indicate whether a customer is likely to default or not. The analysis includes data preprocessing, exploratory data analysis (EDA), handling missing values, outlier detection, and visualizations.

## Objectives
- Identify key factors that contribute to credit risk
- Perform thorough data cleaning and preprocessing
- Visualize trends and patterns to support decision-making
- Provide actionable insights for financial risk assessment

## Tools and Technologies Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Jupyter Notebook

## Key Steps Performed
1. *Data Cleaning:*
   - Removed columns with over 50% missing values
   - Handled null values and fixed data types
2. *EDA (Exploratory Data Analysis):*
   - Univariate, Bivariate, and Multivariate Analysis
   - Derived meaningful metrics and insights
3. *Outlier Detection:*
   - Used IQR and visualization methods to identify and treat outliers
4. *Target Variable Analysis:*
   - 91.2% of applicants did not default
   - 8.8% of applicants defaulted on loans
5. *Visualization:*
   - Bar plots, pie charts, and categorical analysis

## Project Structure
- CREDIT_PROJECT.ipynb: Main Jupyter Notebook with full analysis
- credit_data.csv: Original dataset
- images/: Contains all visualizations used in the report
- final_report.pdf: (Optional) Summary report with key insights

## Insights
- High default rates were observed in specific income and employment types
- Applicants with poor credit history showed high risk of default
- Feature selection is critical for training machine learning models (future scope)

## Author
*Umar Farooq*
