 # 💓 Heart Disease Prediction using Machine Learning

This project aims to predict the presence of heart disease using machine learning algorithms — **Logistic Regression** and **Random Forest**. It uses the [UCI Heart Disease Dataset](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci) and includes detailed steps from preprocessing to model evaluation.

---

## 📌 Table of Contents
- [Project Overview]
- [Dataset Info]
- [Tools & Libraries]
- [Modeling Approach]
- [Results](#results)
- [Confusion Matrices]
- [How to Run](#how-to-run)
- [Future Improvements]

---

## 📋 Project Overview

Heart disease is one of the leading causes of death globally. Early prediction can save lives. This project builds ML models to classify whether a patient is at risk of heart disease based on 16 clinical features.

---

## 🧠 Dataset Info

- Source: UCI Cleveland Heart Disease Dataset
- Total samples: 920 (736 train / 184 test after split)
- Target: `1` = Disease Present, `0` = No Disease
- Features include age, sex, resting blood pressure, cholesterol, max heart rate, etc.

---

## 🛠️ Tools & Libraries

- Python 3.13
- NumPy, Pandas
- Scikit-learn
- Seaborn & Matplotlib
- Jupyter Notebook

---

## 🔍 Modeling Approach

1. **Exploratory Data Analysis (EDA)**
2. **Train-Test Split (80-20)**
3. **Logistic Regression**
   - CV accuracy: ~79%
   - Some convergence warnings due to scale
4. **Random Forest**
   - CV accuracy: ~77.6%
5. **Evaluation using Confusion Matrix**

---

## 📊 Results

- **Logistic Regression Confusion Matrix:**
  - True Positives: 84
  - True Negatives: 64
  - False Positives: 11
  - False Negatives: 25

- **Random Forest Confusion Matrix:**
  - True Positives: 91
  - True Negatives: 67
  - False Positives: 8
  - False Negatives: 18

---

## 📈 Confusion Matrices

| Logistic Regression | Random Forest |
![image](https://github.com/user-attachments/assets/1667e1ec-6d1f-4192-ac6b-f0ffa0886eed)


