EDA Project
This is my first project as an Intern at HexSoftwares, where I performed Exploratory Data Analysis (EDA) on a student dataset to uncover insights into academic performance and influencing factors.

 Project Overview
The goal of this project is to analyze student data to understand how various factors—such as demographics, study habits, attendance, and socio-economic background—affect academic outcomes (final_result).

The notebook follows a structured EDA workflow:

Data loading and initial inspection

Data cleaning and preprocessing

Univariate and multivariate analysis

Visualization of key relationships

Preparation for further modeling

 Dataset: student_info.csv
The dataset contains 1000 student records with the following columns:

student_id, name, gender, age, grade_level

math_score, reading_score, writing_score

attendance_rate, parent_education, study_hours

internet_access, lunch_type, extra_activities

final_result (Pass/Fail)

 Key Steps Performed
Data Loading & Inspection

Loaded data using pandas

Checked structure with .head(), .tail(), .shape, .describe()

Identified unique values in categorical columns

Data Cleaning

Checked for missing values (none found)

Dropped irrelevant columns: attendance_rate, parent_education, extra_activities

Exploratory Data Analysis

Visualized relationships between scores and gender using seaborn.relplot()

Examined score distributions across grade levels

Analyzed categorical features like lunch_type and internet_access

Visualization

Used matplotlib and seaborn for insightful plots

Explored correlations between math_score, reading_score, and writing_score

Technologies Used
Python

Pandas & NumPy for data manipulation

Matplotlib & Seaborn for visualization

Jupyter Notebook for interactive analysis

Key Insights
Strong positive correlation between math_score and reading_score

study_hours and internet_access appear influential in performance

Gender shows slight variation in score distributions

No missing data ensured a clean dataset for modeling

 Future Scope
This EDA lays the foundation for predictive modeling (e.g., classification to predict final_result) and can be extended with:

Feature engineering

Machine learning models

Hyperparameter tuning

Deployment of a student performance predictor
