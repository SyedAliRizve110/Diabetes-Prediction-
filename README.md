# Diabetes Prediction Using Support Vector Machines (SVM)

This repository contains a machine learning project that predicts the likelihood of diabetes in patients based on specific medical measurements. By leveraging a **Support Vector Machine (SVM)** classifier, the model draws an optimal decision boundary to categorize individuals as diabetic or non-diabetic.

## 🚀 Overview

Early detection of diabetes can significantly improve patient outcomes. This project implements an end-to-end machine learning pipeline—including data preprocessing, feature scaling, model training, and performance evaluation—to deliver accurate and reliable risk assessments.

### Key Features
* **Data Preprocessing & Scaling:** Handles missing values and uses 'StandardScaler' to normalize features for optimal SVM performance.
* **SVM Classification:** Implements a Support Vector Machine classifier with tuned hyperparameters (linear/RBF kernel).
* **Comprehensive Evaluation:** Measures performance using Accuracy, Precision, Recall, F1-Score, and a Confusion Matrix.
* **Predictive System:** Includes a helper script to input custom medical data and get an instant prediction.

## 📊 Dataset

The model is trained on the **PIMA Indians Diabetes Dataset** from NIH, which includes the following features:
* Pregnancies (Number of times pregnant)
* Glucose (Plasma glucose concentration)
* Blood Pressure (Diastolic blood pressure in mm Hg)
* Skin Thickness (Triceps skin fold thickness in mm)
* Insulin (2-Hour serum insulin in mu U/ml)
* BMI (Body mass index: weight in kg/(height in m)^2)
* Diabetes Pedigree Function (Diabetes likelihood based on family history)
* Age (years)

## Tech Stack

* **Language:** Python 3.x
* **Machine Learning:** Scikit-Learn
* **Data Analysis:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn

## Results

* **Training Accuracy:** ~82%
* **Testing Accuracy:** ~79%

*(Note: Replace these with your actual model metrics.)*

## Getting Started

### 1. Clone the Repository
```bash```

Install Dependencies
```pip install -r requirements.txt```

Run the Model
```python train_model.py```
