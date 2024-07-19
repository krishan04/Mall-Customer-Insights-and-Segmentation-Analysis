Mall Customer Insights and Segmentation Analysis
Overview
This project provides a comprehensive analysis of mall customer data to identify distinct customer segments and offer strategic marketing recommendations. It involves data cleaning, exploratory data analysis (EDA), and customer segmentation.

Project Structure
Data Collection and Cleaning

File: Mall_Customers.csv

Process:

Loading Data: Imported the dataset into a pandas DataFrame.
Handling Missing Values: Identified and managed missing values appropriately.
Categorical Encoding: Encoded categorical variables (e.g., gender) where necessary.
Saving Cleaned Data: Saved the cleaned dataset as cleaned_mall_customers.csv.
Summary: The cleaning process addressed missing values, encoded categorical variables, and ensured data integrity, resulting in a dataset ready for analysis.

Exploratory Data Analysis (EDA)

File: EDA.ipynb
Process:
Descriptive Statistics: Calculated statistics for age, annual income, and spending score.
Histograms: Created histograms to visualize the distributions of these variables.
Scatter Plot: Produced a scatter plot of annual income vs. spending score, categorized by gender.
Outputs: The EDA notebook includes visualizations and statistics that offer insights into customer demographics and spending patterns.
Customer Segmentation

File: Clustering.ipynb
Process:
Feature Standardization: Standardized features (age, annual income, spending score) to ensure consistency.
K-Means Clustering: Applied K-Means clustering to segment customers into 5 distinct clusters.
Cluster Visualization: Generated a scatter plot of annual income vs. spending score, colored by cluster.
Outputs: The clustering notebook showcases customer segmentation and provides visual insights into different customer groups based on their spending and income.
Insights and Recommendations

File: Insights_Report.pdf
Process:
Segment Analysis: Analyzed the characteristics of each customer segment to understand their behavior.
Strategic Recommendations: Offered tailored marketing strategies based on segment profiles.
Summary: The report summarizes key findings from the segmentation analysis and provides actionable recommendations for targeted marketing.
