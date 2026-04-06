# 📊 Data-Conscientiousness-MSDS-515-2-2025-Class---Project-1-EDA Diabeties

## 🧠 Project 1: Exploratory Data Analysis (EDA) and Visualization on the Diabetes Dataset

---

### 👤 Student Introduction

Hello, my name is **Opeyemi Omotosho**.  
I am a student of **Meharry Medical College**, majoring in **Masters in Artificial Intellegence**.  

This repository contains my coursework and projects for **Data Conscientiousness (MSDS 515)**.

---

## 📘 About the Course

This repository is created for the class **Data-Conscientiousness-MSDS-515**.  

It is used to organize:
- assignments  
- notebooks  
- reports  
- presentations  
- datasets  
- project documentation  

---

## 📌 Project Title

**Project 1: Exploratory Data Analysis (EDA) and Visualization on a Real-World Dataset**

---

## 🎯 Project Objective

The goal of this assignment is to practice:

- loading real-world CSV data into Python  
- performing exploratory data analysis (EDA)  
- calculating summary statistics  
- creating visualizations  
- interpreting relationships between variables  

This project uses the **Pima Indians Diabetes dataset (`diabetes.csv`)** to analyze patterns related to diabetes outcome.

---

## 📊 Dataset Overview

The dataset contains **768 rows and 9 columns**.  

### Variables:
- Pregnancies  
- Glucose  
- BloodPressure  
- SkinThickness  
- Insulin  
- BMI  
- DiabetesPedigreeFunction  
- Age  
- Outcome  

### Target Variable:
- **Outcome**
  - `0 = No Diabetes`
  - `1 = Diabetes`

---

## 🛠️ Project Tasks

### Part 1: Data Loading
- Load `diabetes.csv` into a pandas DataFrame  

### Part 2: Data Visualization
Create 5 different visualizations:
- Histogram  
- Boxplot  
- Scatter plot (Glucose vs Insulin)  
- Scatter plot (BMI vs SkinThickness)  
- Count plot of Outcome  

### Part 3: Exploratory Data Analysis (EDA)
Calculate:
- Mean  
- Median  
- Range  
- Interquartile Range (IQR)  
- Variance  
- Standard Deviation  
- Covariance  
- Correlation coefficient  

### Part 4: Correlation Analysis
- Correlation heatmap  
- Pairplot  

---

## 🔍 Key Findings

From the analysis:

- **Glucose** is the strongest variable associated with diabetes outcome  
- **BMI** and **Age** also show meaningful relationships  
- **Insulin** contains many zero values → likely missing data  
- Dataset is slightly **imbalanced**  
- **BloodPressure** and **SkinThickness** are weaker predictors  

---

## 📈 Visual Summary

The analysis includes:

- 📊 Histogram (Glucose distribution)  
- 📦 Boxplot (BMI with outliers)  
- 🔵 Scatter (Glucose vs Insulin)  
- 🔵 Scatter (BMI vs SkinThickness)  
- 📊 Count plot (Outcome distribution)  
- 🔥 Correlation heatmap  
- 📉 Pairplot (multi-variable relationships)  

---

## 📁 Repository Structure

```text
Data-Conscientiousness-MSDS-515/
│
├── README.md
├── purpose_of_project/
├── ipynb/
├── dataset/
├── presentation/
├── report/
└── images/
