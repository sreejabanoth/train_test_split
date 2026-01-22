# train_test_split
# AI & ML Internship – Task 5: Train-Test Split & Evaluation Metrics

## 📌 Project Overview
This project demonstrates the implementation of train-test splitting and model evaluation techniques using the **Heart Disease Dataset**.  
A Logistic Regression model was trained to predict whether a person has heart disease based on medical attributes.

The goal of this task is to understand how to properly evaluate machine learning models using key performance metrics.

---

## 📊 Dataset
**Heart Disease Dataset**  
- Source: UCI Machine Learning Repository / Kaggle  
- Objective: Predict presence of heart disease  
- Target Variable: `target`  
  - 0 → No heart disease  
  - 1 → Heart disease present  

---

## 🧰 Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  

---

## 🔍 Steps Performed

### 1️⃣ Data Loading
- Loaded the dataset using Pandas
- Checked structure and feature types

### 2️⃣ Feature & Target Selection
- Features (X) → All columns except `target`
- Target (y) → `target` column

### 3️⃣ Train-Test Split
- Split dataset into:
  - 80% Training Data
  - 20% Testing Data
- Used `random_state` for reproducibility

Purpose:
- Training data → Train the model
- Testing data → Evaluate model performance on unseen data

### 4️⃣ Model Training
- Applied Logistic Regression
- Trained model using training dataset

### 5️⃣ Model Evaluation
Calculated the following metrics:

- **Accuracy**
- **Precision**
- **Recall**
- **Confusion Matrix**
- **Classification Report**

---

## 📈 Evaluation Metrics Explanation

- **Accuracy** → Overall correctness of predictions  
- **Precision** → How many predicted positives were actually correct  
- **Recall** → Ability to correctly detect actual positive cases  
- **Confusion Matrix** → Shows True Positives, True Negatives, False Positives, and False Negatives  

In medical datasets, **Recall is especially important** because missing a disease case can be dangerous.

---
