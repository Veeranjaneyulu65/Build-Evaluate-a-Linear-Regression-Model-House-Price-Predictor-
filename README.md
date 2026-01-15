# 🏠 House Price Prediction (Linear Regression)

## 📌 Objective
Build and evaluate a **Linear Regression model** using the California Housing dataset to predict median house values.  
This project demonstrates the **end-to-end ML workflow**: data loading, EDA, preprocessing, training, evaluation, visualization, and reporting.

---

## 📊 Dataset
- **Source**: California Housing dataset (built into scikit-learn).
- Features: Median income, average rooms, population, etc.
- Target: Median house value (`MedHouseVal`).

---

## ⚙️ Workflow
1. Data loading and preparation.
2. Exploratory Data Analysis (EDA) — distributions, correlations, missing values.
3. Train/test split (80/20).
4. Train Linear Regression model.
5. Evaluate using MAE, RMSE, R².
6. Visualize results (actual vs predicted, residuals).
7. Save model for reuse.

---

## 📈 Results
- **MAE**: ~0.53  
- **RMSE**: ~0.74  
- **R²**: ~0.61  

Plots included in `/images`.

---

## 📦 Requirements
Install dependencies with:
```bash
pip install -r requirements.txt
