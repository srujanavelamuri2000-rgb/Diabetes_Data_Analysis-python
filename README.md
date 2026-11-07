# Diabetes Data Analysis Using Python

## 1. Project Overview

This project focuses on exploratory data analysis (EDA) of a diabetes dataset using Python. The objective is to explore health-related factors, identify patterns and understand how different variables are associated with diabetes outcomes.

## 2. Project Objectives

- Understand the structure and characteristics of the dataset.
- Perform data cleaning and handle missing values.
- Explore relationships between health indicators and diabetes outcomes.
- Create meaningful visualisations.
- Identify key patterns and insights from the data.

## 3. Dataset Description

The dataset contains 768 records and 9 columns.

The variables include:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome

The Outcome variable represents diabetes status:
- 0 – No diabetes
- 1 – Diabetes

## 4. Tools and Technologies

- Python
- Pandas – Data manipulation and cleaning
- NumPy – Numerical operations
- Matplotlib – Data visualisation
- Seaborn – Statistical visualisation
- Jupyter Notebook – Development environment

## 5. Data Cleaning

The following preprocessing steps were performed:

- Checked dataset dimensions and data types.
- Identified missing values.
- Checked duplicate records.
- Identified zero values in selected medical measurement columns.
- Replaced implausible zero measurements in Glucose, BloodPressure, SkinThickness, Insulin and BMI with missing values (NaN).

## 6. Exploratory Data Analysis

The following visualisations were created:

1. Diabetes Outcome Distribution
2. Glucose Levels vs Diabetes Outcome
3. Age Distribution by Diabetes Outcome
4. BMI Distribution by Diabetes Outcome
5. Correlation Heatmap
6. Pregnancies vs Diabetes Outcome

## 7. Key Findings

- Glucose showed the strongest positive correlation with diabetes outcome (0.49).
- BMI showed a positive correlation of 0.31.
- Insulin showed a positive correlation of 0.30.
- Individuals in the diabetes group generally had higher median glucose levels.
- The diabetes group showed higher median age and BMI.
- Individuals in the diabetes group also had a higher median number of pregnancies.

## 8. Conclusion

The exploratory analysis identified several patterns and relationships between health-related variables and diabetes outcomes. Glucose showed the strongest positive correlation with the outcome, followed by BMI and Insulin.

The visualisations also highlighted differences in glucose levels, age, BMI and pregnancies between the two outcome groups.

This project provided practical experience in Python-based data cleaning, exploratory data analysis, statistical summaries and data visualisation.

## 9. Project Files

- `Diabetes_Data_Analysis.ipynb` – Jupyter Notebook containing the complete analysis.
- `README.md` – Project documentation.
- Dataset file – Include only if redistribution is permitted by its source.

---

**Project Type:** Beginner-Level Exploratory Data Analysis  
**Domain:** Healthcare Analytics  
**Language:** Python
