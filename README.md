# Titanic Data Cleaning & Preprocessing

This repository contains my work for Task 1 of the AI & ML Internship program. The objective of this task was to learn and implement data cleaning and preprocessing techniques using the Titanic dataset.

---

## 📝 Task Objective

To clean and prepare raw data for Machine Learning by handling:
- Missing values
- Categorical data
- Feature scaling
- Outlier detection and removal

---

## 📂 Dataset

**Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

## 🛠 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Steps Performed

1. **Data Loading**  
   Loaded the dataset using Pandas.

2. **Exploratory Data Analysis**  
   Checked for null values, data types, and data distribution.

3. **Missing Value Treatment**
   - Filled `Age` with median.
   - Filled `Embarked` with mode.
   - Dropped `Cabin` due to excessive missing data.

4. **Encoding Categorical Variables**
   - Used label encoding for `Sex`.
   - Used one-hot encoding for `Embarked`.

5. **Feature Scaling**
   - Standardized `Age` and `Fare` using `StandardScaler`.

6. **Outlier Detection & Removal**
   - Visualized outliers with boxplots.
   - Removed extreme outliers in `Fare` using IQR method.

---

## 📁 Files Included

- `ElevateLabs_Task1.ipynb` – Jupyter notebook with full implementation
- `titanic.csv` – Dataset used
- `README.md` – This file

---

## ✅ Outcome

Successfully cleaned and preprocessed the Titanic dataset, ready for machine learning model training.
