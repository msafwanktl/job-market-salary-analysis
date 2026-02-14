Job Market Analysis and Salary Prediction Using Data Analytics and Machine Learning
 Project Overview

This project analyzes the global data job market to identify trends in job roles, experience levels, company locations, and salary distributions. Using Python-based data analytics and machine learning techniques, the project also builds predictive models to estimate salaries in USD based on job-related attributes.

 Objectives

Analyze job market trends for data-related roles
Identify high-demand job roles and locations
Understand how experience level impacts salary
Build machine learning models to predict salary in USD
Compare different models and select the best-performing one

 Dataset

Source: Public job salary dataset (Kaggle)
Records: 607 job listings
Target Variable: salary_in_usd

 Key Features:

Job title
Experience level
Employment type
Company location
Company size
Remote work ratio
Work year

 Data Cleaning & Preprocessing

Removed unnecessary index column
Verified and handled missing values
Standardized categorical values (experience level, employment type)
Selected relevant features for analysis
Applied one-hot encoding to categorical variables
Prepared dataset for machine learning models

 Exploratory Data Analysis (EDA)

Key insights from the analysis:
Data Engineer and Data Scientist roles appear most frequently
Salaries vary significantly by job role and experience level
Senior and executive-level roles earn substantially higher salaries
Job opportunities are concentrated in specific company locations
Experience level plays a major role in salary growth

 Machine Learning Models

Two models were trained and evaluated:

1 Linear Regression
RMSE: ~46,258 USD
R² Score: ~0.44

2 Random Forest Regressor

RMSE: ~49,345 USD
R² Score: ~0.36

 Final Model Selected: Linear Regression
Reason: Lower prediction error and better generalization on this dataset.

 Conclusion

This project demonstrates that simpler models such as Linear Regression can outperform more complex models when the dataset size is limited and underlying patterns are reasonably linear. Job role, experience level, company characteristics, and remote work ratio are key factors influencing salary outcomes in the data job market.

 Technologies Used

Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
Google Colab