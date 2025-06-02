# RandomForestRegressor
🔍 Introduction
The Random Forest Regressor is a powerful supervised machine learning algorithm used for predicting continuous values. It works by creating a "forest" of decision trees and taking the average of their predictions — reducing overfitting and increasing accuracy.
# Concrete Strength Prediction 🧱

Predicting the compressive strength of concrete using **Random Forest Regressor** — a powerful ensemble learning method based on decision trees that improves accuracy by combining multiple trees.

---

## 📊 Dataset

- 1030 samples with 8 features:
  Cement, Slag, Fly Ash, Water, Superplasticizer, Coarse & Fine Aggregate, Age
- Target: Concrete compressive strength (MPa)

---

## ⚙️ Model: Random Forest Regressor

- Builds multiple decision trees on random subsets of data/features
- Aggregates their predictions to reduce overfitting and improve generalization
- Suitable for complex, non-linear relationships in data

---

## 🚀 Workflow

1. Data preprocessing
2. Train-test split
3. Model training & prediction
4. Performance evaluation (R², MAE, MSE)

---

## ✅ Results

- R² Score: `88.0`  
- MAE: `3.73`  
- MSE: `29.8`  

## 🛠 Requirements
- Numpy,Pandas
- Seaborn,Matplotlib
- Sklearn library



