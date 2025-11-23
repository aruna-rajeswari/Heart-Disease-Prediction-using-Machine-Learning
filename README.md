❤️ Cardiovascular Disease Analysis & Prediction Using Python & Machine Learning
🧠 1. Introduction

Cardiovascular diseases (CVDs) are among the leading global causes of mortality. Early detection and understanding of contributing factors are essential for prevention and improved clinical decisions.

This project analyzes a medical dataset of 4,000+ patient records and 14 clinical attributes using Python, statistical methods, machine learning, and Tableau visualization.

🎯 Project Objectives

Identify the factors that significantly influence cardiovascular disease

Build a machine learning model to predict heart attack risk

Visualize medical insights using interactive Tableau dashboards

The project integrates EDA, statistical analysis, logistic regression modeling, and BI visualization to deliver a comprehensive perspective on CVD risk.

📥 2. Importing, Understanding & Inspecting Data (Python)
🔍 2.1 Preliminary Data Inspection

Using Pandas, NumPy, Matplotlib, and Seaborn, the dataset was evaluated for:

✔ Dataset size: 4,000+ rows, 14 features

✔ Mixed data types (numeric + categorical)

✔ Missing values in cholesterol and thal attributes

✔ Duplicate entries

✔ Outliers in resting blood pressure and cholesterol

🧹 2.2 Data Cleaning & Preparation

Python techniques applied:

Removal of duplicate records

Missing value handling using:

Median/mean for numerical fields

Mode for categorical fields

Data type corrections

Outlier investigation

This created a clean, reliable dataset ready for EDA and modeling.

📊 2.3 Statistical Summary

df.describe() provided:

Central tendency (mean, median)

Variability (standard deviation, percentiles)

Detection of skewness in medical metrics

These insights guided feature engineering and modeling.

🔎 3. Exploratory Data Analysis (EDA in Python)
🧬 3.1 Categorical Variable Exploration

Categorical fields such as sex, chest pain type, fasting blood sugar, exercise-induced angina, and thalassemia were visualized using:

Count plots

Bar charts

Frequency tables

This helped understand overall patient distributions.

👵🧓 3.2 CVD Occurrence by Age

CVD risk increases significantly with age

Highest prevalence seen in individuals aged 50+

💓 3.3 Resting Blood Pressure vs Heart Attack Risk

Higher BP values showed association with CVD

BP alone is not a strong standalone predictor

🚹🚺 3.4 Gender Composition

More male patients in the dataset

Males show higher CVD prevalence

Females show increasing risk with advancing age

🚀 4. In-Depth EDA & Machine Learning Modeling
🩸 4.1 Cholesterol Levels

Higher cholesterol values correlate with increased CVD risk

Non-linear patterns → multivariate ML model required

🏃‍♂️❤️ 4.2 Peak Exercise Metrics (Thalach & Angina)

Lower max heart rate (thalach) → higher disease risk

Exercise-induced angina strongly linked to CVD

🧫 4.3 Thalassemia & Other Predictors

Strong associations found with:

Thalassemia type

Age

Chest pain type

Max heart rate

Resting ECG

🔁 4.4 Pair Plot Analysis

Using Seaborn pairplots:

Multi-feature interactions visualized

Clear clusters between healthy vs diseased groups

🤖 4.5 Logistic Regression Model

Machine learning workflow:

Data split into train/test sets

Logistic Regression model trained

Predictions evaluated using:

✔ Accuracy

✔ Precision

✔ Recall

✔ F1 Score

✔ Confusion Matrix

The model performed well as a baseline predictor for CVD.

📊 5. Visualization & Dashboarding (Tableau)
🖥️ 5.1 Diseased vs Healthy Dashboard

Tableau dashboards visualized:

Age distribution

Cholesterol & blood pressure

Max heart rate

Chest pain type

Gender breakdown

Thalassemia categories

🔗 5.2 Relationship & Risk Factor Dashboard

The dashboard illustrated:

Interactions among multiple variables

High-risk feature combinations

Patterns correlating strongly with CVD

Interactive filters enabled detailed exploration for subgroups.

🏁 6. Conclusion

This project successfully demonstrates how Python, machine learning, and BI tools can provide meaningful insights into cardiovascular diseases.

✔ Key Achievements

Cleaned and explored a comprehensive medical dataset

Identified major CVD determinants:

Age

Cholesterol

Chest pain type

Max heart rate

Exercise-induced angina

Developed a strong baseline predictive model

Built Tableau dashboards for clinical interpretation

This project highlights how data science can support early diagnosis, preventive strategies, and informed medical decisions in cardiovascular healthcare.
