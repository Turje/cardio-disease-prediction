# Predicting Cardiovascular Disease Using Machine Learning and Ensemble Learning

This repository contains the final project for the **Applied Machine Learning** graduate course at The City College of New York.

## Project Report

The full research paper — *Predicting Cardiovascular Disease Using Classification Models and Ensemble Learning* — outlines our methodology, feature engineering, modeling, and results in detail.

[Read the full report](./Predicting_Cardiovascular_disease_using_classification_models.pdf)

# Contents

- `Final_Project_AML2025.ipynb` – Jupyter notebook with all preprocessing, modeling, and evaluations.
- `Predicting_Cardiovascular_disease_using_classification_models.pdf` – Final project research paper.
- `data/cardio_train.csv` – Data set from Kaggle.
- `requirements.txt` – List of Python packages.

## Summary

We evaluated six classification models (logistic regression, decision trees, random forest, KNN, XGBoost, CatBoost) using a dataset of ~70,000 datapoints. Engineered clinical features and ensemble learning (stacking and soft voting) significantly improved performance. The best model achieved a ROC-AUC of **0.805** on the test set.

---

**Authors:** Saar Turjeman, Safal Thapa  
**Course:** Applied Machine Learning, 2025  
**Institution:** The City College of New York
