# Hotel Cancellations Predictive Analysis

## Project Overview

This machine learning project analyzes and predicts hotel booking cancellations.  
Using a dataset of **83,293 hotel bookings** with **33 features**, the project identifies key factors driving cancellation behavior and builds predictive classification models.

---

## Dataset Information

- **Total Records:** 83,293  
- **Total Features:** 33  
- **Target Variable:** `is_canceled`  
  - 0 = Not Canceled  
  - 1 = Canceled  

### Feature Categories

**Booking Details**
- Lead time  
- Arrival date  
- Stay duration  

**Guest Information**
- Adults  
- Children  
- Babies  

**Hotel Specifics**
- Hotel type  
- Room assignments  
- Meal plans  

**Booking Modifications**
- Booking changes  
- Deposit type  
- Special requests  

---

## Project Scope

**Objective:**  
Predict which hotel bookings are likely to be canceled.

**Business Use Cases:**
- Revenue optimization  
- Operational planning  
- Overbooking management  

**Approach:**  
Supervised classification using multiple machine learning algorithms.

---

## Technologies & Libraries

### Data Processing
- Pandas  
- NumPy  

### Data Visualization
- Matplotlib  
- Seaborn  
- Plotly  

### Machine Learning
- scikit-learn  
- XGBoost  
- LightGBM  

### Model Interpretation
- SHAP  
- DALEX  
- ELI5  

### Class Imbalance Handling
- SMOTE (Synthetic Minority Over-sampling Technique)

---

## Models Implemented

- Logistic Regression  
- Support Vector Classifier (SVC)  
- Random Forest Classifier  
- XGBoost Classifier  
- LightGBM Classifier  

---

## Analysis Workflow

### 1. Data Preprocessing
- Feature engineering  
- Encoding categorical variables  
- Handling missing values  

### 2. Exploratory Data Analysis (EDA)
- Cancellation pattern analysis  
- Feature distribution analysis  

### 3. Model Training
- Training multiple classification algorithms  
- Hyperparameter tuning  

### 4. Model Evaluation
- Accuracy  
- Classification report  
- Confusion matrix  

### 5. Model Interpretability
- SHAP value analysis  
- Feature importance evaluation  

---

## Expected Outcome

A predictive model capable of identifying high-risk cancellation bookings, enabling hotels to:

- Improve revenue forecasting  
- Optimize overbooking strategies  
- Enhance operational efficiency  
