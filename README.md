# Task 3 – Linear Regression

This repository contains the solution for **Task 3** of my AI & ML Internship.  
The goal of this task is to apply **Linear Regression** to predict a continuous variable from the Heart Disease dataset.

---

## 📊 Dataset Used

**Heart Disease Dataset**  
(Same dataset used in Task 1 and Task 2 for consistency)

| Feature       | Description                              |
|----------------|------------------------------------------|
| Age           | Age of the patient                       |
| Cholesterol   | Serum cholesterol level                  |
| MaxHR         | Maximum heart rate achieved              |
| Oldpeak       | ST depression induced by exercise        |
| RestingBP     | (Target) Resting blood pressure (mm Hg)  |

---

## 🧠 Objective

To predict the `RestingBP` (Resting Blood Pressure) based on:
- Age
- Cholesterol
- MaxHR
- Oldpeak

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- Scikit-learn
- Matplotlib

---

## 📈 Steps Performed

1. **Loaded and prepared the data**
2. **Split the dataset** into training and test sets
3. **Trained a Linear Regression model** using `sklearn.linear_model`
4. **Evaluated** the model using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score
5. **Plotted** the Actual vs Predicted values
6. **Interpreted model coefficients**

---

## 📊 Evaluation Metrics

| Metric   | Value (Example) |
|----------|------------------|
| MAE      | ~12.26           |
| MSE      | ~150.92          |
| R² Score | ~0.23            |

---

## 🔍 Interpretation

- R² = 0.23 → 23% of variation in RestingBP is explained by the model.
- Oldpeak had the highest influence (coefficient) on RestingBP.
- More features or better data could improve performance.

---

## 📁 Folder Contents

| File Name                     | Description                                |
|------------------------------|--------------------------------------------|
| `task3_linear_regression.ipynb` | Notebook with code and output           |
| `README.md`                  | This documentation                         |
| `heart.csv`                  | (Optional) Dataset if not downloaded live  |

---

## 🎯 Learning Outcome

Through this task, I learned:
- How Linear Regression works
- How to interpret coefficients and metrics
- How to visualize regression results

