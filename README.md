# Bank-Loan-Case-Study
In this project, we will perform Exploratory Data Analysis (EDA) on a dataset containing information about loan applicants and their previous loan applications. The goal of this analysis is to gain insights into the factors that are significant in determining a customer's likelihood of defaulting on a loan.
# Dataset Description:
The dataset consists of two CSV files: "application_data.csv" and "previous_application.csv."
The "application_data.csv" file contains information about current loan applicants, including
their demographics, financial attributes, and loan status. On the other hand, the
"previous_application.csv" file contains data related to previous loan applications made by
these same applicants.
# Objective:
Our main objective is to identify key variables and attributes that play a crucial role in
determining whether a loan should be provided to a customer or not. Through EDA, we aim
to uncover meaningful patterns and correlations in the data that can help us make informed
decisions and create a predictive model for loan default prediction.
# Steps for EDA:
## 1. Data Cleaning and Preprocessing:
● Remove irrelevant columns from both datasets.
● Handle missing values appropriately by imputation or removal.
● Convert categorical variables into a suitable format for analysis.
## 2. Univariate Analysis:
● Explore the distribution of each variable to understand its range and spread.
● Use visualizations such as histograms, box plots, and bar charts to examine
data characteristics.
## 3. Bivariate Analysis:
● Analyze the relationship between loan attributes and customer attributes.
● Identify correlations and patterns between variables that can impact loan
approval.
## 4. Data Visualization:
● Create various visualizations such as scatter plots, heatmaps, and correlation
matrices to uncover trends and insights.
● Visualize the distribution of loan amounts, income levels, and other key
variables.
## 5. Outlier Detection:
● Use quartiles and Interquartile Range (IQR) to identify potential outliers in the
data.
● Visualize outliers through box plots and assess their impact on loan approval.
## 6. Merge Datasets:
● Merge the two datasets based on the common identifier "SK_ID_CURR" to
combine information about previous loan applications with current loan
applicants.
## 7. Correlation Analysis:
● Calculate correlation coefficients between various variables to determine
their interdependence.
● Focus on variables that have a strong correlation with loan default.
## 8. Feature Importance:
● Rank variables based on their significance in predicting loan default using
correlation analysis results.
# Conclusion:
Through thorough Exploratory Data Analysis, we will gain valuable insights into the factors
that influence loan approval and default. This analysis will serve as the foundation for
further predictive modeling to develop a robust loan default prediction system. The results
and recommendations from this project will be valuable for financial institutions in making
informed decisions about loan approvals and mitigating the risk of default.
