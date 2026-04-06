📊 Overview of the Dataset

The dataset used in this project is the Pima Indians Diabetes Dataset, a well-known healthcare dataset used for predictive analysis and exploratory data analysis.

It contains 768 patient records and 9 variables (columns). Each row represents one individual, and the goal is to understand factors associated with diabetes.

🧾 Structure of the Dataset

The dataset consists of:

768 rows (observations)
9 columns (features + target)

Each column represents a medical or demographic measurement related to a patient.

🧩 Variables Explained
1. Pregnancies
Number of times the patient has been pregnant
Integer value
Important for understanding hormonal and metabolic changes
2. Glucose
Plasma glucose concentration (blood sugar level)
One of the most important variables
Higher values strongly indicate diabetes risk
3. BloodPressure
Diastolic blood pressure (mm Hg)
Measures cardiovascular health
Some values may be unrealistic (e.g., 0), indicating missing data
4. SkinThickness
Triceps skin fold thickness (mm)
Used to estimate body fat
Often has zero values, which may represent missing data
5. Insulin
2-hour serum insulin level
Helps measure how the body regulates blood sugar
Highly variable with many zero values (likely missing data)
6. BMI (Body Mass Index)
Weight-to-height ratio
Strong indicator of obesity
Obesity is closely linked to diabetes risk
7. DiabetesPedigreeFunction (DPF)
Indicates genetic predisposition to diabetes
Higher values → higher hereditary risk
8. Age
Age of the patient (years)
Diabetes risk increases with age
9. Outcome (Target Variable)
Indicates whether the patient has diabetes
0 = No Diabetes
1 = Diabetes

This is the dependent variable used for prediction.

📌 Key Characteristics of the Dataset
✔️ Type of Data
Structured, tabular data
Mix of numerical features and binary target
✔️ Class Distribution
More non-diabetic (0) than diabetic (1)
Slight class imbalance
✔️ Data Quality Issues
Several columns contain zero values, which are not realistic:
Insulin
SkinThickness
BloodPressure
These likely represent missing or unrecorded data
✔️ Variability
Some variables (like Insulin) have very high variability
Others (like DPF) are more tightly distributed
🔍 What This Dataset Is Used For

This dataset is commonly used for:

Exploratory Data Analysis (EDA)
Data cleaning and preprocessing practice
Classification modeling (predicting diabetes)
Feature importance analysis
Healthcare data insights
