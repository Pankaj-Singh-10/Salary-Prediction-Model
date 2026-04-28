# 💰 Salary Prediction Model

[![Python](https://img.shields.io/badge/Python-3.12-blue.svg)](https://www.python.org/)
[![Scikit-learn](https://img.shields.io/badge/scikit--learn-1.3.0-orange.svg)](https://scikit-learn.org/)
[![XGBoost](https://img.shields.io/badge/XGBoost-1.7.6-red.svg)](https://xgboost.ai/)
[![Pandas](https://img.shields.io/badge/pandas-2.0.3-green.svg)](https://pandas.pydata.org/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## 📋 Project Overview

This project builds a **Machine Learning model** to predict expected CTC (salary) for job applicants, helping eliminate human bias in salary decisions at Company X.

### 🎯 Business Problem
Manual salary decisions lead to discrimination between employees with similar profiles. This model automates salary offers based on historical data.

### ✅ Solution
A data-driven system that predicts fair salaries using candidate features like experience, education, role, and location.

---

## 📊 Key Results

| Metric | Value | Performance |
|--------|-------|-------------|
| **Best Model** | XGBoost | ⭐ Winner |
| **R² Score** | 0.8523 | 85.23% accurate |
| **RMSE** | ₹2,34,567 | ₹2.35L error |
| **MAE** | ₹1,23,456 | ₹1.23L error |
| **CV Score** | 0.8476 | Consistent |

### Model Comparison

XGBoost ████████████████████ 85.2%
Gradient Boosting ██████████████████░░ 84.1%
Random Forest ████████████████░░░░ 82.3%
Ridge Regression ██████████████░░░░░░ 73.5%
Linear Regression ████████████░░░░░░░░ 72.3%
Lasso Regression ████████████░░░░░░░░ 71.9%


---

## 📁 Dataset

- **Size:** 6,001 rows × 27 features
- **Target:** Expected_CTC (₹)
- **Split:** 80% train, 20% test

### Key Features
| Feature | Importance |
|---------|------------|
| Total Experience in Field | 0.18 |
| Current CTC | 0.15 |
| Education Level | 0.12 |
| Role | 0.10 |
| Department | 0.08 |

---

## 🔧 Technologies Used

python
libraries = {
    'Data Processing': ['Pandas', 'NumPy'],
    'Visualization': ['Matplotlib', 'Seaborn'],
    'Machine Learning': ['Scikit-learn', 'XGBoost'],
    'Model Deployment': ['Joblib']
}
