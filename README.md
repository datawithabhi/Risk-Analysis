# Risk Analysis: Uncovering Key Factors Influencing Loan Default Rates

## Problem Statement

This repository contains a comprehensive exploratory data analysis (EDA) of loan data with the aim of identifying and mitigating credit loss, the primary financial loss due to borrower defaults ('charged-off' customers). The goal is to uncover significant driver variables behind loan defaults through EDA, enabling better risk assessment and reduction of high-risk loans.

## Business Understanding

The project revolves around a consumer finance company specializing in providing various types of loans to urban customers. The company faces the challenge of determining whether to approve or reject loan applications based on the applicant’s profile. Two types of risks are associated with the bank’s decision: approving a loan to a likely defaulter and rejecting a loan from a likely payer. The objective is to use EDA to understand how consumer attributes and loan attributes influence the tendency of defaulting.

## Dataset

The dataset used for this analysis is sourced from past loan applicants, containing information about their attributes and whether they defaulted on the loan. The data includes various attributes such as loan amount, term, interest rate, grade, employment length, home ownership, annual income, verification status, loan status, purpose, debt-to-income ratio, and more.

The dataset used in this analysis can be accessed from the following link:
[Kaggle Loan Dataset](https://www.kaggle.com/datasets/abhiganeshkar/loan-dataset?select=loan.csv)

## Exploratory Data Analysis (EDA)

The EDA process involves the following key steps:

### Data Cleaning and Preparation
- Handling missing values and outliers in the dataset.
- Correcting data types to ensure consistency and accuracy.
- Creating new categorical variables for analysis.

### Univariate Analysis
- Analyzing individual variables to understand their distribution and characteristics.
- Visualizing categorical variables using bar plots and pie charts.
- Visualizing numerical variables using box plots and histograms.

### Bivariate Analysis
- Analyzing the relationship between two variables, both categorical and numerical.
- Exploring how loan status is influenced by various attributes such as grade, employment length, home ownership, verification status, and more.
- Identifying patterns and trends that indicate higher default risk.

### Multivariate Analysis
- Analyzing the interaction of multiple variables simultaneously.
- Exploring how factors like loan term, grade, employment length, home ownership, and verification status collectively influence loan default rates.

## Conclusion

Through thorough exploratory data analysis, we have gained valuable insights into the factors that significantly influence loan default rates. These insights can be used to enhance risk assessment strategies, allowing the company to make more informed decisions when approving or rejecting loan applications. By understanding the relationship between borrower attributes and loan defaults, the company can better manage credit risk and optimize their lending practices.

For a detailed analysis of the data and visualizations, refer to the Jupyter Notebook provided in this repository.
