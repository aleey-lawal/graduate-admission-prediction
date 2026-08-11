# 🎓 Predicting Graduate Admissions with Logistic Regression

A data-driven machine learning project that models graduate admission outcomes using Logistic Regression. This project transforms applicant profiles into probabilistic insights to support informed decision-making.

The original dataset had 500 rows and 9 columns. Cleaning steps: (1) dropped the auto-generated index column Serial No. and Unnamed: 0; (2) stripped trailing whitespace from column names; (3) renamed the target column to Admission_Outcome; (4) confirmed zero nulls and zero duplicates. No imputation was required.

## Dataset
**Source:** [Graduate Admissions – Kaggle](https://www.kaggle.com/datasets/mohansacharya/graduate-admissions)  
**Author:** Mohan S Acharya  
**License:** CC0: Public Domain

---

## 📌 Overview

Graduate admissions are influenced by multiple factors such as academic performance, test scores, and research experience. This project leverages **Logistic Regression**, a classification algorithm, to predict whether a candidate is likely to be admitted based on these features.

The goal is to:
- Understand key factors influencing admission decisions  
- Build a predictive model for classification  
- Translate raw data into actionable insights  

---

## 🧠 Problem Statement

Given a dataset of applicant profiles, can we accurately predict whether a candidate will be admitted?

This is framed as a **binary classification problem**, where:
- `1` → Admitted  
- `0` → Not Admitted  

---

## 📊 Dataset

The dataset includes features such as:
- GRE Score  
- TOEFL Score  
- University Rating  
- Statement of Purpose (SOP)  
- Letter of Recommendation (LOR)  
- CGPA  
- Research Experience  

> 📁 *Source: Kaggle Graduate Admissions Dataset*

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Handling missing values  
- Feature scaling (Standardization)  
- Encoding categorical variables (if applicable)  

### 2. Exploratory Data Analysis (EDA)
- Correlation analysis  
- Distribution plots  
- Feature importance insights  

### 3. Model Building
- Logistic Regression model implementation  
- Train-test split (e.g., 80/20)  

### 4. Model Evaluation
- Accuracy Score  
- Confusion Matrix  
- Precision, Recall, F1-Score  

---

## 📈 Results

- The model successfully captures key admission patterns  
- Strong predictors include **CGPA, GRE Score, and Research Experience**  
- Provides probability-based predictions for better interpretability  

---

## 🛠️ Tech Stack

- **Python**  
- **Pandas & NumPy** – Data manipulation  
- **Matplotlib & Seaborn** – Visualization  
- **Scikit-learn** – Machine Learning  

