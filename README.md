Project Overview
This project performs exploratory data analysis (EDA) on a restaurant inspection dataset containing over 290,000 rows and 27 columns. The primary goal is to clean the data, engineer new features, visualize insights, and analyze restaurant inspection patterns using statistics and charts.​

Objectives
Understand the restaurant inspection dataset

Clean and preprocess the data

Discover trends and outliers

Perform statistical tests (e.g., t-test, chi-square, ANOVA)

Univariate, bivariate, and multivariate analysis

Visualize main results using charts

Dataset Description
Source: Restaurant Inspection Dataset

Total Rows: 290,022

Columns include: CAMIS, DBA, BORO, BUILDING, STREET, ZIPCODE, PHONE, CUISINE DESCRIPTION, INSPECTION DATE, ACTION, VIOLATION CODE, VIOLATION DESCRIPTION, CRITICAL FLAG, SCORE, GRADE, etc.

Main Steps Performed
Data Loading: Imported main libraries (pandas, numpy, matplotlib, seaborn, scipy) and loaded the CSV file.

Initial Exploration: Used head(), tail() to view sample records and columns.

Data Cleaning:

Checked null values per column and filled them as needed

Standardized column names and dropped unrelated columns

Changed datatypes, especially date columns

Removed duplicates

Filled missing grades based on score bands

Feature Engineering:

Created a numeric grade column (A=1, B=2, C=3, N=4)

Filtered outliers and replaced with mean or median

Statistical Analysis:

Chi-square test for relationship between location and grade

Independent t-test for mean inspection score between boroughs

ANOVA for mean scores across locations

One-sample t-test for population vs sample mean

Visualizations:

Distribution plot of grades

Boxplot of scores (outliers handling)

Count of restaurants per borough

Additional charts for scores and grades

Key Results
Significant relationships were observed between restaurant location and grade (chi-square, ANOVA tests)

Differences in inspection scores across boroughs

Outlier handling improved statistical integrity

Conclusion
The notebook cleans and analyzes the restaurant dataset, drawing insights via statistical tests and data visualizations. It prepares the data for further machine learning or business analysis.

Requirements
Python 3.x

pandas, numpy, matplotlib, seaborn, scipy

Usage
Open and run the cells sequentially in Jupyter/Colab to follow the full EDA workflow.
