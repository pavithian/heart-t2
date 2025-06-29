# Task 2 – Exploratory Data Analysis (EDA)

This repository contains the solution for **Task 2** of my AI & ML Internship.  
The goal of this task is to explore and understand the dataset using visualizations and descriptive statistics.

---

## 📊 Dataset Used

**Heart Disease Dataset**  
(Same dataset used in Task 1 for consistency)

| Feature         | Description                            |
|-----------------|----------------------------------------|
| Age             | Age of the patient                     |
| Sex             | Gender (Male/Female)                   |
| ChestPainType   | Type of chest pain                     |
| RestingBP       | Resting blood pressure                 |
| Cholesterol     | Serum cholesterol level                |
| FastingBS       | Fasting blood sugar (0 or 1)           |
| RestingECG      | Resting electrocardiographic results   |
| MaxHR           | Maximum heart rate achieved            |
| ExerciseAngina  | Exercise-induced angina (Yes/No)       |
| Oldpeak         | ST depression during exercise          |
| ST_Slope        | Slope of the ST segment                |
| HeartDisease    | Target variable (1 = Yes, 0 = No)      |

---

## 🔧 Tools & Libraries Used

- Python
- Pandas
- Matplotlib
- Seaborn

---

## 📈 Steps Performed

### 1. **Summary Statistics**
- Used `.describe()` to understand mean, median, std, etc.
- Checked value distributions.

### 2. **Histograms**
- Plotted histograms for numeric features like Age, Cholesterol, MaxHR, etc.

### 3. **Boxplots**
- Used to detect outliers in features like Oldpeak and Cholesterol.

### 4. **Correlation Matrix**
- Heatmap showed relationships between features.
- Noted that `Oldpeak` and `MaxHR` are correlated with `HeartDisease`.

### 5. **Pairplot**
- Visualized feature relationships and class separability for `HeartDisease`.

---

## 🧠 Key Observations

- **Oldpeak** has a strong positive relation with heart disease.
- **MaxHR** and **Age** negatively influence heart disease risk.
- **Cholesterol** has weak correlation with the target.
- Some outliers exist in Cholesterol and Oldpeak values.

---

## 📝 Folder Contents

| File Name        | Description                          |
|------------------|--------------------------------------|
| `eda_task2.ipynb`| Notebook with all code and charts    |
| `README.md`      | This documentation                   |
| `heart.csv`      | (Optional) Dataset if not from Kaggle|

---

## 🎯 Learning Outcome

Through this task, I practiced how to:
- Explore data visually
- Interpret correlations
- Identify patterns and outliers
- Derive insights for machine learning models

