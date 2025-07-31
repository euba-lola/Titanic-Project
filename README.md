# 🚢 Titanic Survival Prediction – Machine Learning Classification Report

## 📌 Project Title:
**Predicting Passenger Survival on the Titanic Using Machine Learning Algorithms**

---

## 1. Introduction

This project involves the development of a machine learning model that predicts whether a passenger survived the Titanic disaster. The dataset used is a historical record from the Titanic tragedy, provided by [Kaggle](https://www.kaggle.com/competitions/titanic/data), and contains information about passengers such as their age, sex, class, fare, and family relationships aboard the ship.

The goal is to build a predictive classification model that accurately determines the survival status of passengers using these features.

---

## 2. Problem Statement

The aim of this classification task is to predict the survival status of Titanic passengers (`1 = Survived`, `0 = Did not survive`) using the available dataset. By analyzing various demographic and travel-related features, the model seeks to uncover patterns associated with survival outcomes.

---

## 3. Dataset Overview

- **Source:** Titanic dataset from Kaggle  
- **Number of rows:** 891  
- **Number of columns:** 12  

### Key Features:
- `Pclass` (Passenger class)  
- `Sex`  
- `Age`  
- `SibSp` (Number of siblings/spouses aboard)  
- `Parch` (Number of parents/children aboard)  
- `Fare`  
- `Embarked` (Port of embarkation)  
- `Cabin`  
- `Ticket`

### Feature Engineering:
- **Deck:** Extracted from the `Cabin` column (first letter)  
- **Ticket_Number:** Numeric part extracted from the `Ticket` field  

---

## 4. Methodology

### a. Data Preprocessing
- Handled missing values appropriately  
- Converted categorical variables using encoding  
- Engineered new features such as `Deck` and `Ticket_Number`  

### b. Exploratory Data Analysis (EDA)
- Analyzed feature distributions  
- Explored relationships with survival outcome  
- Visualized patterns using seaborn and matplotlib  

### c. Model Building
Applied multiple supervised learning algorithms:
- Logistic Regression  
- Random Forest Classifier  
- Support Vector Machine (SVM)  

### d. Model Evaluation
Evaluated models using:
- Accuracy  
- Confusion Matrix  
- ROC-AUC Score  

---

## 5. Results

Each model’s performance was compared. The model with the best overall evaluation metrics (especially AUC) was selected and interpreted. Insights from feature importance and model performance are discussed in the notebook.

---

## 6. Tools and Technologies Used

- **Language:** Python  
- **Environment:** Jupyter Notebook  
- **Libraries:**  
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - scikit-learn  

---
