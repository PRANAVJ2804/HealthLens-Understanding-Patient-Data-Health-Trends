# 📊 HealthLens – Patient Health Trends & Risk Insights

## 🧠 Project by:  Pranav J, Rohit Sharma, and Bhumika Jain

---

## 📌 Project Description

This project analyzes health records to identify patterns in cardiovascular risk and patient demographics. The dataset includes clinical variables such as age, sex, cholesterol, blood pressure, and more. Our objective is to uncover insights that can assist medical professionals in early detection and improved healthcare planning.
**Dataset Source:** [Heart Disease UCI Dataset](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci)

---

## 🎯 Problem Statement

Cardiovascular diseases remain a leading cause of death worldwide. Identifying patterns from patient data is critical in improving diagnosis and prevention. This project aims to:
- Understand relationships between key health indicators and heart disease.
- Identify high-risk demographic and clinical profiles.
- Offer insights to improve screening and targeted health interventions.

---

## 📖 Table of Contents

1. [Project Overview](#project-overview)
2. [Data Understanding](#data-understanding)
3. [Data Cleaning](#data-cleaning)
4. [Exploratory Data Analysis (EDA)](#eda)
5. [Insights Derived](#insights-derived)
6. [Suggestions](#suggestions)
7. [Challenges Faced](#challenges-faced)
8. [Future Scope](#future-scope)
9. [Final Outcome](#final-outcome)
10. [SQL Analysis File](#sql-analysis-file)
11. [Project Credits](#project-created-by)

---

## 🧩 Project Overview

We analyzed patient health records to uncover trends influencing heart disease risk. The focus areas included:
- Age and gender distribution in heart risk.
- Influence of clinical metrics like cholesterol and blood pressure.
- Comparison between exercise response and disease presence.

---

## 🧾 Data Understanding

- The dataset consists of structured medical data with fields like:
    - 'age', 'sex', 'cholesterol', 'resting_bp', 'max_heart_rate', etc.
- Binary target variable: heart disease status.
- No missing values, but renaming and encoding were required.
- Derived fields like age_group were added for better insights.

---

## 🧼 Data Cleaning

- Renamed ambiguous columns for clarity (e.g., cp → chest_pain_type).
- Encoded numerical categories into readable strings:
    - sex: 1 → Male, 0 → Female
    - fasting_blood_sugar: 1 → "Possible Diabetes"
- Derived columns:
    - age_group: Binned into Middle-aged, Senior, and Old.
- Removed duplicates and ensured consistent formatting.

---

## 📊 EDA

### 🧵 Distribution of Grades
![Distribution of Grades](./Images/distribution_of_grades.png)

### 👥 Student Gender Breakdown
![Distribution by Gender](./Images/distribution_by_gender.png)

### 📊 Count by Gender and Group
![Gender & Group Count](./Images/count_gender_group.png)

### 📈 Average Score by Subject
![Average Score by Subject](./Images/average_score_by_subject.png)

### 📊 Gender-wise Subject Scores
![Average Score by Gender](./Images/average_score_by_gender.png)

### 👨‍👩‍👧‍👦 Score by Group & Parental Education
![Score by Group & Education](./Images/score_by_group_and_parental_education.png)

### 🍱 Lunch & Test Preparation
![Performance by Lunch & Test Prep](./Images/performance_by_lunch_and_test_prep.png)

### 📘 Test Prep Impact by Gender & Group
![Test Prep by Gender & Group](./Images/test_prep_by_gender_and_group.png)

### 🔥 Correlation Heatmap
![Correlation Heatmap](./Images/correlation_heatmap.png)

---

## 📍 Insights Derived

1. **Age Influence**
   - Risk increases sharply after age 50.
   - Seniors had the highest positive cases.

2. **Gender-Based Differences**
   - Males show a slightly higher incidence of heart disease.

3. **Cholesterol & BP**
   - Patients with high resting blood pressure and cholesterol levels are more prone.

4. **Exercise Indicators**
   - Patients experiencing chest pain during exercise are at higher risk.

5. **ECG and Thallium**
   - Abnormal results were common in diagnosed individuals.

---

## 💡 Suggestions

1. **Early Screenings for Seniors**
   - Periodic ECG, cholesterol, and BP checkups for people above 50.

2. **Promote Exercise Readiness Programs**
   - Tailored fitness programs for those showing angina symptoms.

3. **Awareness by Gender**
   - Gender-specific awareness and screening campaigns.

4. **Lifestyle Monitoring**
   - Focus on dietary and stress interventions for at-risk groups.

5. **Data-Driven Decisions**
   - Health institutions can use EDA to prioritize high-risk cases.

---

## ⚠️ Challenges Faced

- Handling categorical variable encodings and renaming them appropriately.
- Interpreting medically significant variables without misrepresenting.
- Correlating non-linear patterns like cholesterol vs age.

---

## 🚀 Future Scope

- Integrate machine learning models for heart disease prediction.
- Expand dataset to include multiple hospitals or time series trends.
- Develop a risk-scoring dashboard for clinical use.

---

## ✅ Final Outcome

This project provided a comprehensive view of how patient health metrics contribute to cardiovascular risks. We identified key indicators and developed visual reports that medical staff or policy-makers can act on.

---
## 🗂️ SQL Analysis File

You can find the SQL queries and logic used for backend analysis in the following file:

📄 [`SQL Analysis File.sql`](https://github.com/A-Patel23/Student-Performance-Project/blob/73b25c892568192beb2295825f49907f9a32a6fc/Sql%20File/SQL%20Analysis%20File.sql)

---

## 🎓 Project Created By

**Pranav J**, **Rohit Sharma**, and **Bhumika Jain**
---
