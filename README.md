...Telco Customer Churn Analysis

## Project Overview

This project explores customer churn in a telecommunications company using Python and exploratory data analysis (EDA).

The goal is to identify patterns and customer characteristics associated with churn and translate the findings into actionable business recommendations.

## Objectives

* Clean and prepare the dataset for analysis.
* Explore customer characteristics and service usage.
* Analyze churn patterns across contracts, payment methods, and additional services.
* Investigate relationships between customer tenure, monthly charges, and churn.
* Summarize key findings and provide business recommendations.

## Dataset

The dataset contains 7,043 customer records and 21 columns, including:

* Customer demographics
* Contract information
* Internet and phone services
* Payment methods and billing preferences
* Tenure and charges
* Customer churn status

The target column is Churn, which indicates whether a customer has left the service (Yes) or remained (No).

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Project Structure
CUSTOMER-CHURN-ANALYSIS/
├── data/
│   ├── cleaned_Telco-Customer-Churn.csv
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── notebooks/
│   ├── 01-data_cleaning.ipynb
│   └── 02_Exploratory_Data_Analysis.ipynb
└── .gitignore
|__ README.md
## Analysis Workflow

### 1. Data Cleaning

* Inspected the dataset structure and data types.
* Checked for missing values and duplicate records.
* Prepared the data for exploratory analysis.
* Converted TotalCharges to a numeric data type.

### 2. Exploratory Data Analysis

* Examined the overall distribution of customer churn.
* Compared churn rates across contract types.
* Analyzed customer tenure and monthly charges.
* Investigated churn patterns across demographic characteristics.
* Explored relationships involving internet services, technical support, payment methods, and billing preferences.
* Examined correlations between numerical features and churn.
* Visualized the relationship between tenure and monthly charges.

## Key Findings

* Approximately 26.5% of customers in the dataset had churned.
* Month-to-month contracts had the highest churn rate (42.71%).
* Two-year contracts had a much lower churn rate (2.83%).
* Customers who churned had a lower average tenure (17.98 months) than customers who remained (37.57 months).
* Customers who churned had higher average monthly charges (74.44) than customers who remained (61.27).
* Customers using electronic check payments had a churn rate of 45.29%.
* Customers without online security or technical support had higher observed churn rates than customers with those services.

## Business Recommendations

Based on the observed patterns, the analysis suggests that the company could:

* Investigate retention strategies for customers on month-to-month contracts.
* Review pricing and service experiences among customers with higher monthly charges.
* Examine the early customer journey to identify potential reasons for churn.
* Investigate customer satisfaction and service quality among fiber-optic internet users.
* Evaluate the needs of customers who do not use online security or technical support.
* Explore why electronic check users have a higher observed churn rate.

These recommendations are based on exploratory findings and require further investigation before implementation.

## Limitations

* This project focuses on data cleaning and exploratory data analysis.
* Observed relationships do not establish causation.
* No machine learning model or churn prediction system is included in this project.
* Further statistical analysis and customer research would be needed to validate potential explanations.

## Conclusion

This project demonstrates the use of Python-based data cleaning, exploratory analysis, visualization, and business interpretation to investigate customer churn.


The findings highlight several customer segments that may benefit from further investigation and targeted retention strategies.


## Data Source and Acknowledgments

* Dataset: Telco Customer Churn
* Source: [Kaggle – Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
* Original dataset: IBM Sample Data
* File: WA_Fn-UseC_-Telco-Customer-Churn.csv
* Dataset size: 7,043 customer records and 21 columns.

This dataset is used for educational purposes to perform data cleaning, exploratory data analysis (EDA), data visualization, and business insight generation.

The analysis focuses on identifying customer churn patterns and developing data-driven business recommendations. No machine learning model is included in this project.