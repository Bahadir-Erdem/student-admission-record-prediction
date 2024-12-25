# **Student Admission Analysis and Model Pipeline**

This project aims to analyze and predict student admissions using a machine learning pipeline. The workflow covers data preprocessing, exploratory data analysis (EDA), feature engineering, and model selection. The project incorporates a variety of tools, such as `scikit-learn`, `CatBoost`, `XGBoost`, and `LightGBM`, with an emphasis on robust feature selection and hyperparameter tuning.

Best results found using:
- Classifier: Catboost
- Feature Selection Method: RFE(Recursive Feature Elimination)

---

## **Pipeline**
![Pipeline][pipeline]

## **Scores**
![Classification Report][classification_report]
---
![Auroc Curve][auroc_curve]


## **Overview**
This project implements a complete machine learning pipeline to predict student admission outcomes based on various features such as:
- Age
- Gender
- Admission Test Score
- High School Percentage
- City
- Admission Status (Target)

The notebook includes:
- **Exploratory Data Analysis (EDA)**: Insights into distributions, relationships, and patterns.
- **Preprocessing**: Handling missing values, outliers, and feature scaling.
- **Feature Engineering**: Including polynomial feature generation and multiple feature selection methods(kbest, rfe, catboost feature selection).
- **Model Training**: Comparing multiple classifiers with hyperparameter optimization.
- **Performance Evaluation**: Using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.

---

## **Dataset**
The dataset is taken from [kaggle][dataset_url].

[dataset_url]: https://www.kaggle.com/datasets/zeeshier/student-admission-records/data
[pipeline]: images/pipeline.png
[classification_report]: images/classification_report.png
[auroc_curve]: images/auroc_curve.png