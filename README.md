# 🧠 Predicting Mortality in Liver Cirrhosis Patients Using Machine Learning

## Overview

This project evaluates the effectiveness of three machine learning models — **Logistic Regression**, **Random Forest**, and **XGBoost** — in predicting mortality among patients diagnosed with liver cirrhosis. The work emphasizes clinical interpretability and practical utility in identifying high-risk patients.

## 🔬 Clinical Motivation

Chronic liver diseases, particularly cirrhosis, remain a leading cause of morbidity and mortality worldwide. Early identification of at-risk patients enables timely interventions and resource optimization. This project aims to explore the role of ML models in supporting such clinical decisions.

## 📁 Project Structure

| File                     | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| `PART1-3.ipynb`          | Data loading, preprocessing, EDA, feature engineering, and SMOTE balancing |
| `PART4-5.ipynb`          | Model training, evaluation (ROC, PR, AUC), and interpretation               |
| `הוראות למטלה.docx.pdf` | Project instructions (in Hebrew)                                             |
| `מטלת הגשה - רז.docx`   | Final report (in Hebrew)                                                    |

## 📊 Key Techniques

- Outlier filtering and data cleaning
- Feature engineering and categorical encoding
- Imbalanced classification with **SMOTE**
- ML models: Logistic Regression, Random Forest, XGBoost
- Evaluation using **ROC AUC**, **Precision-Recall Curves**, and **Confusion Matrices**

## 🛠 Technologies

- Python 3.x
- Jupyter Notebooks
- Libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `xgboost`
  - `imbalanced-learn`
  - `matplotlib`, `seaborn`

## 🚀 How to Run

1. Clone the repository:
   ```bash
gh repo clone RaDoN135/-Predicting-Mortality-in-Liver-Cirrhosis-Patients-Using-Machine-Learning 
cd liver-cirrhosis-mortality-prediction
