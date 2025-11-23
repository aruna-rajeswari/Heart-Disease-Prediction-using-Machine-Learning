# ❤️ Cardiovascular Disease Analysis and Prediction  
### Using Python, Machine Learning & Data Visualization

---

## 📘 1. Introduction  

Cardiovascular diseases (CVDs) remain one of the leading causes of death worldwide.  
Early prediction and an understanding of risk factors are essential for improving patient outcomes.

This project analyzes a medical dataset containing **4,000+ patient observations** across **14 clinical attributes** using:  
- Python  
- Statistical Data Analysis  
- Exploratory Data Analysis (EDA)  
- Machine Learning (Logistic Regression)  
- Visual Insights using Python  

### 🔍 Project Objectives  
1. Identify key factors contributing to cardiovascular disease  
2. Build a machine learning model to estimate heart attack risk  
3. Visualize insights using Python  

This project integrates EDA, statistical evaluation, ML modeling, and visual dashboards to provide a complete analytical view of CVD risk prediction.

---

## 📥 2. Importing, Understanding & Inspecting Data  

### 🔍 2.1 Preliminary Data Inspection  
Using Pandas, NumPy, Matplotlib, and Seaborn, the dataset was assessed for:  
- **Structure:** 4,000+ rows, 14 features  
- **Types:** Numerical + categorical  
- **Missing Values:** Cholesterol & thal-related fields  
- **Duplicates:** Several duplicate rows detected  
- **Outliers:** High values in cholesterol and resting BP  

---

### 🧹 2.2 Data Cleaning & Preparation  
Python was used to:  
- Remove duplicate records  
- Impute missing values using:  
  - Mean/Median → numerical  
  - Mode → categorical  
- Fix incorrect data types  
- Identify outliers in sensitive medical variables  

This ensured a clean, reliable dataset for further analysis.

---

### 📊 2.3 Statistical Summary  
Using `df.describe()`, we examined:  
- Central tendency (mean, median)  
- Dispersion (std deviation, percentiles)  
- Skewness in multiple health metrics  

This statistical foundation guided feature understanding.

---

## 🔎 3. Exploratory Data Analysis (EDA in Python)

### 🧬 3.1 Categorical Variables  
Explored clinical categories such as:  
- Gender  
- Chest pain type  
- Fasting blood sugar flag  
- Exercise-induced angina  
- Thalassemia  

Visualization methods used:  
- Count plots  
- Bar charts  
- Frequency tables  

---

### 👵 3.2 CVD Occurrence by Age  
Key findings:  
- CVD prevalence increases significantly with age  
- Highest risk among patients **50+ years old**

---

### 💓 3.3 Resting Blood Pressure  
- Elevated BP shows correlation with CVD  
- However, BP alone is not a strong standalone predictor  

---

### 🚹 3.4 Gender Composition  
- More male patients in dataset  
- CVD higher in males but increases in females with age  

---

## 🚀 4. In-Depth EDA & Machine Learning Modeling  

### 🩸 4.1 Cholesterol Levels and CVD  
- Higher cholesterol → higher CVD risk  
- Non-linear relationship → ML modeling required  

---

### 🏃‍♂️ 4.2 Peak Exercise Metrics  
Analysis of **thalach** and exercise-induced angina revealed:  
- Lower max heart rate → higher risk  
- Angina during exercise strongly linked with CVD  

---

### 🧫 4.3 Thalassemia & Other Predictors  
Strong predictors included:  
- Thalassemia  
- Age  
- Chest pain type  
- Max heart rate  
- Resting ECG results  

---

### 📈 4.4 Pair Plot Analysis  
Seaborn pairplots revealed:  
- Clear clustering between healthy vs diseased groups  
- Multivariate interactions useful for ML modeling  

---

### 🤖 4.5 Machine Learning Model — Logistic Regression  

**Process:**  
- Applied train-test split  
- Trained Logistic Regression model  
- Generated predictions on the test set  

**Model Evaluation:**  
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

Outcome: A strong baseline model supporting early CVD detection.

---

## 📊 5. Visualization in Python  

### 🩺 5.1 Diseased vs Healthy Comparison  
Python visual dashboards were used to compare:  
- Age distribution  
- Cholesterol levels  
- Resting BP  
- Maximum heart rate  
- Gender, chest pain type, thalassemia  

These visuals clearly differentiated key characteristics of healthy vs diseased patients.

---

### 🔗 5.2 Risk Factor Interaction Visuals  
Insights include:  
- Interaction of variables such as **thalach, BP, cholesterol**  
- Detection of high-risk combinations  
- Visual patterns identifying major risk contributors  

---

## 🏁 6. Conclusion  

This project successfully integrates **Python programming, statistical analysis, machine learning, and visualization** to analyze cardiovascular disease risk.

### ✔ Key Outcomes  
- Comprehensive data cleaning and EDA  
- Identified major CVD determinants such as age, cholesterol, chest pain type, and exercise-induced angina  
- Developed an effective Logistic Regression model for prediction  
- Produced clear and actionable medical insights using visual analytics  

This study highlights how data science can enhance healthcare diagnostics and support preventive strategies.

---

## 🛠 Tech Stack  
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)  
- **Jupyter Notebook**  
- **Data Visualization using Python**
