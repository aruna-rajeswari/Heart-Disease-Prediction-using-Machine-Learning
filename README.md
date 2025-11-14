Cardiovascular Disease Analysis and Prediction Using Python and Machine Learning
1. Introduction
Cardiovascular diseases (CVDs) remain one of the leading causes of death worldwide. Early prediction and an understanding of risk factors are essential for improving patient outcomes. This project uses Python and machine learning to analyze a medical dataset containing over 4,000 patient observations across 14 clinical attributes.
The main objectives were:
1.	Determine the factors that significantly contribute to cardiovascular diseases
2.	Build a predictive machine learning model to estimate heart attack risk
3.	Visualize insights using Tableau
By integrating exploratory data analysis (EDA), statistical evaluation, logistic regression modeling, and dashboarding, this project delivers a comprehensive view of CVD risk prediction using modern data analytics tools.

2. Importing, Understanding, and Inspecting Data (Python)
2.1 Preliminary Data Inspection
Using Python libraries such as Pandas, NumPy, and Matplotlib/Seaborn, the dataset was explored to determine:
•	Dataset structure: 4,000+ rows and 14 attributes
•	Data types: A mix of numerical and categorical features
•	Missing values: Present in cholesterol and thal-related columns
•	Duplicate entries: Several duplicate rows were identified
•	Outliers: Extreme values in resting blood pressure and cholesterol
2.2 Data Cleaning and Preparation
Python was used to:
•	Remove duplicate records
•	Impute missing values using:
o	Median or mean for numerical variables
o	Mode for categorical variables
•	Check and correct data types
•	Conduct outlier awareness for sensitive variables
This ensured a clean and reliable dataset for EDA and modeling.
2.3 Statistical Summary
A preliminary summary was generated using df.describe(), providing:
•	Measures of central tendency (mean, median)
•	Measures of dispersion (standard deviation, percentiles)
•	Detection of skewness in several medical metrics
This summary guided further analysis and feature interpretation.

3. Exploratory Data Analysis (EDA in Python)
3.1 Identification of Categorical Variables
Categorical features such as sex, chest pain type, fasting blood sugar indicator, exercise-induced angina, and thalassemia were explored using:
•	Count plots
•	Bar charts
•	Frequency tables
These visualizations provided an overview of patient distributions.
3.2 CVD Occurrence by Age
Python visualizations revealed:
•	Increasing CVD prevalence with age
•	Highest risk among individuals aged 50 years and above
3.3 Resting Blood Pressure and Heart Attack Detection
•	Elevated resting blood pressure showed an association with CVD
•	However, BP alone was not a definitive predictor
3.4 Gender Composition
•	More male patients were present in the dataset
•	CVD was more common in males, though females showed increased risk with age

4. In-Depth EDA and Machine Learning Modeling
4.1 Cholesterol Levels and CVD
•	Higher cholesterol levels corresponded with increased CVD occurrence
•	The relationship was nonlinear, indicating the need for multivariate modeling
4.2 Peak Exercise Metrics
Using attributes like max heart rate (thalach) and exercise-induced angina:
•	Lower peak exercise capacity correlated with higher disease risk
•	Patients with angina during exercise had significantly elevated CVD risk
4.3 Thalassemia and Other Factors
Analysis showed:
•	Certain thalassemia types strongly associated with CVD
•	Additional influential predictors included age, chest pain type, max heart rate, and resting ECG
4.4 Pair Plot Analysis
Using Seaborn’s pairplot:
•	Multivariate relationships were visualized
•	Clear distinctions appeared between healthy and diseased individuals
•	Allowed observation of feature clusters relevant to modeling
4.5 Logistic Regression Model in Python
A machine learning model was developed using Python’s scikit-learn library:
•	Data split into training and testing sets
•	Logistic Regression model trained on the training data
•	Predictions generated on the test set
A confusion matrix and classification metrics were used to evaluate model performance:
•	Accuracy
•	Precision
•	Recall
•	F1 Score
The model served as a strong baseline for CVD prediction, demonstrating how machine learning can support clinical decision-making.

5. Visualization and Dashboarding in Tableau
5.1 Diseased vs Healthy Comparison Dashboard
A Tableau dashboard was created to illustrate:
•	Age distribution
•	Cholesterol and blood pressure levels
•	Max heart rate achieved
•	Categorical factors such as chest pain type, gender, and thalassemia
This helped distinguish key differences between healthy and diseased individuals.
5.2 Relationship and Risk Factor Dashboard
The dashboard further demonstrated:
•	How multiple variables interact
•	High-risk patterns (e.g., low thalach + high BP)
•	Feature combinations that strongly correlate with CVD
Interactive filters provided deeper exploration for different patient subgroups.

6. Conclusion
This project successfully combined Python programming, machine learning, and data visualization to analyze cardiovascular disease risk factors and predict heart attack likelihood. Key achievements include:
•	Comprehensive data cleaning and exploration using Python
•	Identification of major CVD determinants such as age, cholesterol, chest pain type, and exercise-induced angina
•	Development of a logistic regression model with strong predictive power
•	Clear visualization of medical insights using Tableau dashboards
By integrating analytical and predictive techniques, this project demonstrates how data science can play a critical role in advancing cardiovascular health diagnostics and prevention strategies.

