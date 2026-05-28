# Diabetes Prediction Using Advanced Machine Learning
ML-based diabetes prediction system
## Project Overview

This project aims to predict diabetes using advanced supervised machine learning techniques based on medical diagnostic parameters such as glucose level, BMI, insulin, blood pressure, and age.

The project focuses on improving prediction accuracy using advanced preprocessing, feature engineering, imbalance handling, and ensemble learning techniques.

---

## Problem Statement

The primary objective of this project is to design, evaluate, and optimize an advanced diabetes classification model capable of accurately predicting whether a patient is diabetic or non-diabetic.

---

## Dataset Information

The dataset contains medical attributes such as:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
- Outcome (Target Variable)

Dataset Size:
- 768 records
- Binary Classification Problem

---

## Technologies & Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Imbalanced-Learn (SMOTE)

---

## Advanced Techniques Used

### Data Preprocessing
- Missing value handling
- KNN Imputation
- Feature Scaling using StandardScaler

### Feature Engineering
Created smart features such as:
- BMI_Age_Ratio
- Glucose_Insulin_Ratio
- High_Glucose
- High_BMI

### Handling Imbalanced Data
- SMOTE (Synthetic Minority Oversampling Technique)

---

## Machine Learning Models Used

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier
- Stacking Classifier (Ensemble Learning)

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Cross-Validation Accuracy

---

## Visualizations Included

- Correlation Heatmap
- Confusion Matrix
- ROC Curve
- Precision-Recall Curve
- Feature Importance Graph
- Violin Plots

---

## Results

### Logistic Regression
- Accuracy: ~69%
- ROC-AUC: ~0.81

### Random Forest
- Accuracy: ~72%
- ROC-AUC: ~0.82

### Advanced Stacking Model
- Accuracy: ~74%
- ROC-AUC: ~0.817

The ensemble-based approach improved prediction performance and handled complex medical patterns effectively.

---

## Project Structure

```bash
Diabetes-ML-Classification/
│
├── dataset/
├── results/
├── models/
├── README.md
├── requirements.txt
├── diabetes_prediction.py
├── diabetes_prediction.ipynb
└── Diabetes_Project_Report.docx
```

---

## How to Run

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Project

```bash
python diabetes_prediction.py
```

---

## Future Improvements

- Deep Learning Integration
- Explainable AI (XAI)
- Streamlit/Flask Deployment
- Real-Time Prediction System

---

## Author

Yashika Rajput
