# Pima Diabetes Data Analysis Project

## Overview
This project analyzes the **Pima Indian Diabetes dataset** to identify key diabetes risk factors and patterns using **Excel**. The dataset was enhanced with calculated fields to support advanced analysis. The final product is an **interactive dashboard** with slicers, pivot tables, and visualizations to dynamically explore insights.

---

## Dataset
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/pima+indians+diabetes)
- **Original Dataset Features:**
  - `Pregnancies`: Number of pregnancies.
  - `Glucose`: Plasma glucose concentration (mg/dL).
  - `BloodPressure`: Diastolic blood pressure (mm Hg).
  - `SkinThickness`: Triceps skinfold thickness (mm).
  - `Insulin`: 2-hour serum insulin (mu U/ml).
  - `BMI`: Body Mass Index.
  - `DiabetesPedigreeFunction`: Genetic predisposition to diabetes.
  - `Age`: Age in years.
  - `Outcome`: 1 = Diabetes, 0 = No Diabetes.

---

## Modifications
The dataset was enhanced with the following **calculated columns**:
1. **Age Brackets:**
   - Categorized patients into groups:
     - `<30`, `30-50`, `50+`.
       
2. **Risk Level:**
   - Classified patients as:
     - `High` (if Glucose > 140 or BMI > 30).
     - `Normal` (otherwise).
       
3. **Pregnancy Count Groups:**
   - Grouped pregnancy counts into categories:
     - `No Pregnancy`, `1-2`, `3-4`, `5-6`, `7+`.
---

## Dashboard Features
- **Interactive Slicers:**
  - Filter data dynamically by:
    - `Age Bracket`
    - `Risk Level`
    - `Outcome`
    - `Pregnancy Count`

- **Visualizations:**
  1. **Bar Chart:** Diabetes prevalence by pregnancy count and age bracket.
  2. **Pie Chart:** High-risk vs. normal patient distribution.
  3. **Line Chart:** Average glucose, BMI, insulin, and blood pressure by outcome.
  4. **Stacked Bar Chart:** Risk level distribution across age groups.
  5. **Column Chart:** Genetic predisposition (Diabetes Pedigree Function) by diabetes outcome.

---

## Key Insights
1. **Age and Risk Levels:**
   - Age brackets `30-50` and `50+` have the highest proportion of high-risk individuals.
2. **Pregnancy and Diabetes:**
   - Higher pregnancy counts (e.g., `7+`) are more prevalent in diabetic patients.
3. **Key Metrics:**
   - Diabetic patients exhibit:
     - Higher glucose levels (~141 vs. 110).
     - Higher BMI and insulin levels on average.
4. **Genetic Predisposition:**
   - Diabetic patients have a higher average Diabetes Pedigree Function (~0.55 vs. 0.43).

---

## How to Use
1. **Download the Files:**
   - Clone or download the repository.
   - Open `pima_diabetes.xlsx` in Microsoft Excel.
2. **Explore the Dashboard:**
   - Use slicers to filter the data dynamically.
   - Review the pivot tables and visualizations for insights.

---
