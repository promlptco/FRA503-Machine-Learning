# FRA503-Machine-Learning

A collection of supervised learning assignments covering **regression and classification** tasks on datasets.

## Overview

This repository contains three machine learning projects implementing end-to-end ML pipelines including data preprocessing, exploratory data analysis, feature engineering, model training, and evaluation.

---

## Projects

### HW01: Medical Charge Prediction (Regression)

**Problem Type:** Supervised Regression

**Objective:** Predict hospital charges for patients using clinical and demographic features.

**Dataset:** SUPPORT2 (Study to Understand Prognoses Preferences Outcomes and Risks of Treatment)
- 9,105 hospitalized patients from five U.S. states (1989-1994)
- Target variable: `charges` (continuous, right-skewed distribution)
- Features: Age, sex, length of stay, disease group, vital signs, lab values

**Key Tasks:**
- Exploratory data analysis with distribution analysis
- Feature classification (categorical vs continuous)
- Handling missing values and outliers
- Statistical analysis and correlation studies

---

### HW02: In-Hospital Mortality Prediction (Classification)

**Problem Type:** Supervised Binary Classification

**Objective:** Predict in-hospital death (hospdead) for critically ill patients.

**Dataset:** SUPPORT2
- Same patient population as HW01
- Target variable: `hospdead` (binary: yes/no)
- Features: Clinical measurements, demographics, disease categories

**Key Tasks:**
- Binary classification problem formulation
- Data leakage identification and prevention
- Feature selection and engineering
- Handling imbalanced classes
- Model validation strategies

---

### Project: Bank Marketing Campaign Prediction (Classification)

**Problem Type:** Supervised Binary Classification

**Objective:** Predict whether a client will subscribe to a term deposit based on marketing campaign data.

**Dataset:** Bank Marketing (Portuguese Banking Institution)
- Direct phone marketing campaign records
- Target variable: `y` (binary: yes/no subscription)
- Features: Age, job, marital status, education, account balance, housing loan, contact information

**Machine Learning Models:**
- Logistic Regression
- K-Nearest Neighbors (KNNs)
- Decision Tree
- Random Forest

**Experimental Design:**
- 4 data preprocessing pipelines
- 16 unique model-pipeline configurations (4 models × 4 pipelines)
- 5-fold cross-validation
- Primary evaluation metric: Mean ROC-AUC score

**Model Assumptions Addressed:**
- Logistic Regression: Linearity, multicollinearity, normality of residuals, homoscedasticity
- KNN: Locality hypothesis, feature scaling requirements
- Decision Tree: No strict distributional assumptions
- Random Forest: Ensemble of decision trees with bootstrap sampling

## Group Members

- Chantouch Orungrote (66340500011)
- Penpitcha Chobchon (66340500035)
- Sasish Kaewsing (66340500076)

## Technical Stack
**Libraries:**
```
numpy
pandas
matplotlib
seaborn
scikit-learn
scipy
ucimlrepo
```
