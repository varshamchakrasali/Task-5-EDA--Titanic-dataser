# Task-5-EDA--Titanic-dataser

Task-5-Titanic-Dataset---Exploratory-Data-Analysis-EDA-
🚢 Titanic Dataset - Exploratory Data Analysis (EDA)
This project is part of Task 5 from a Data Analyst Internship, focused on performing Exploratory Data Analysis (EDA) on the Titanic dataset using Python.

🎯 Objective
Explore the Titanic dataset using Pandas, Matplotlib, and Seaborn
Visualize patterns, trends, and correlations
Handle missing data effectively
Document observations and summarize insights in a clear, structured format

🧰 Tools & Libraries Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

📝 Steps Performed
Data Loading
Loaded the Titanic dataset (train.csv) into a Pandas DataFrame.

Initial Exploration

Used .info(), .describe(), .isnull().sum() to understand structure & missing values.
Data Cleaning

Filled missing values in Age with the median
Filled missing values in Embarked with the mode
Dropped the Cabin column due to too many missing entries
Univariate Analysis

Plotted histograms and countplots for variables like Age, Sex, Pclass, etc.
Bivariate Analysis

Analyzed survival rate by gender, class, fare using boxplots and violin plots
Correlation Analysis

Created a heatmap to show correlations among numerical variables
Used pairplot to analyze multivariate interactions
Summary

Documented insights from visual and statistical EDA
Prepared the dataset for modeling and further analysis

📂 Files Included
Titanic_EDA_Task5.ipynb – Jupyter Notebook with full analysis
Titanic_EDA_Task5.pdf – PDF version of the notebook
train.csv – Dataset used for the analysis
README.md – Project overview (you are here)

🔍 Key Insights
👩‍🦰 Females had a significantly higher survival rate
🛳️ 1st class passengers were more likely to survive
💰 Passengers who paid higher fares had better chances of survival
👶 Younger passengers (children and young adults) showed better survival trends
✅ Cleaned dataset is ready for machine learning or advanced analytics
🔗 Dataset Source
→ Titanic - Machine Learning from Disaster | Kaggle

📌 Notes
This project is a part of Task 5 of my Data Analyst Internship to demonstrate proficiency in:

Exploratory Data Analysis
Data Cleaning
Visual Storytelling
Generating actionable insights
