# AI-Powered Job Market Insights
## Project Overview
This project explores the modern job market with a focus on AI and automation across various industries. Using the “AI-Powered Job Market Insights” dataset, which includes 500 unique job listings, the project aims to analyze the impact of AI on employment. The dataset features job titles, industry, company size, location, AI adoption level, automation risk, required skills, annual salary in USD, remote-friendly status, and job growth projection.

**Steps and Analysis**
1. **Importing Libraries and Loading the Dataset**
Essential libraries such as pandas, numpy, matplotlib, seaborn, and others were imported. The dataset was loaded for analysis.

2. **Exploratory Data Analysis (EDA)**
Data Overview: Displayed the first and last five rows of the dataset.
Dataset Shape: Confirmed the dataset has 500 rows and 10 columns.
Column Information: Listed and checked the data types of each column.
Statistical Overview: Provided a summary of the Salary_USD column.
Null Values: Verified there are no null values in the dataset.
Unique Values: Counted unique values in key columns.
3. **Data Preprocessing**
Data Cleaning: Handled outliers using the Interquartile Range (IQR) method.
Duplicates: Checked for and confirmed there are no duplicate records.
4. **Data Analysis**
Required Skills Analysis: Grouped and visualized required skills by AI adoption level.
Word Cloud: Created a word cloud to visualize the most common skills required for the jobs.
Scatter Geo Plot: Used plotly.express to create a scatter geo plot showing job locations and counts.
5. **Predictive Analysis Model Building**
Salary Prediction
**Feature Engineering:** Selected categorical features (Job_Title, AI_Adoption_Level, Automation_Risk, Required_Skills) and scaled the salary data using StandardScaler.
**One-Hot Encoding:** Converted categorical variables into a format suitable for machine learning models.
Data Preparation: Combined the encoded categorical features with the scaled salary data.
**Train-Test Split:** Split the data into training and testing sets.
**Model Training:** Built and trained an XGBRegressor model to predict salaries.
**Model Evaluation:** Evaluated the model performance using Root Mean Squared Error (RMSE), which was found to be 1.194.
**Prediction Visualization:** Visualized the actual vs. predicted salaries using a scatter plot.

**Conclusion**
This project provides a comprehensive analysis of the AI-powered job market, including data preprocessing, exploratory data analysis, visualizations, and predictive modeling. Further steps will include refining the model and exploring additional features to improve prediction accuracy.

