# Titanic Survival Prediction  | Machine Learning Project

This project is based on the famous **Titanic dataset** where the goal is to predict whether a passenger survived or not using machine learning classification models.

It includes data preprocessing, feature engineering, model training, and evaluation.

---

##  Project Overview

The Titanic disaster is one of the most well-known shipwrecks in history. This dataset contains passenger information such as age, gender, ticket class, fare, etc.

The objective is to build a model that can predict:

- **Survived (1)** → Passenger survived  
- **Not Survived (0)** → Passenger did not survive

---

##  Dataset

Dataset used: **Kaggle Titanic Dataset**

Main files:
- `train.csv` → Training dataset (includes survival labels)
- `test.csv` → Testing dataset (no labels)
---

##  Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook

---

##  Steps Performed

### 1. Data Loading
Loaded the Titanic dataset using Pandas.

### 2. Data Cleaning
Handled missing values in features like:
- Age
- Embarked
- Cabin (dropped or simplified)

### 3. Feature Engineering
Converted categorical values into numerical form using:
- Label Encoding / One-Hot Encoding

Common engineered features:
- Sex → Male/Female conversion
- Embarked → Port categories conversion
- Pclass → Passenger class as feature

### 4. Model Training
Trained classification models such as:
- Logistic Regression
- Decision Tree
- Random Forest (if used)

### 5. Model Evaluation
Evaluated the model using:
- Accuracy Score
- Confusion Matrix
- Classification Report

---

##  Results

The model successfully predicts passenger survival with good accuracy after preprocessing and feature engineering.

