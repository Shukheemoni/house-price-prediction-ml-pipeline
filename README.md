# 🏠 House Price Prediction – End-to-End ML Pipeline

## Overview
This project implements an end-to-end machine learning pipeline to predict house sale prices using the **Ames Housing dataset**. The focus of the project is on proper **feature engineering**, **missing value handling**, and building a **leakage-free preprocessing and modeling workflow** using scikit-learn pipelines.

This project was developed as part of a structured learning process and demonstrates core machine learning best practices for tabular data.

---

## Problem Statement
Predict house sale prices based on numerical and categorical housing features.  
This is a **supervised regression problem**.

---

## Dataset
- **Ames Housing Dataset**
- Contains numerical and categorical variables related to property characteristics
- Includes missing values and mixed data types, making it suitable for demonstrating real-world preprocessing challenges

---

## Modeling Approach
- Performed exploratory data analysis (EDA)
- Applied feature engineering and missing value handling
- Built an end-to-end **Pipeline** using:
  - `ColumnTransformer`
  - Numerical imputation (mean / median)
  - Categorical imputation (most frequent)
  - One-Hot Encoding
- Ensured **data leakage prevention** by applying all preprocessing inside the pipeline
- Trained and evaluated a regression model on a held-out test set

---

## Evaluation Metric
- **RMSE (Root Mean Squared Error)**  
Chosen because it penalizes large prediction errors, which is appropriate for house price prediction.

---

## Key Learnings
- How to structure a clean machine learning workflow using pipelines
- Importance of avoiding data leakage in preprocessing
- Handling mixed data types in tabular datasets
- Building reproducible and scalable ML code

---

## Project Structure
