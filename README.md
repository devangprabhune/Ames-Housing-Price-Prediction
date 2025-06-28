# Ames-Housing-Price-Prediction
Machine Learning Project- House Price Prediction
# 🏠 House Price Prediction - Ridge and Lasso Regression

This project predicts house prices using **regularized linear regression** on the popular Ames Housing dataset.

---

## 📌 Project Overview

- **Goal:** Build a robust regression model to predict the `SalePrice` of a house using various features such as lot size, number of rooms, year built, etc.
- **Methods Used:**
  - Data Cleaning & Preprocessing
  - Feature Selection (`SelectKBest`)
  - Ridge Regression
  - Lasso Regression
  - Model Evaluation (RMSE & R²)
  - Out-of-sample prediction
  - Model & result export

---

## ⚙️ Tools & Libraries

- Python 3.x
- Google Colab (for GPU/CPU power)
- `pandas`, `numpy`
- `scikit-learn`

---

## 📊 Model Results

| Model | Train RMSE | Test RMSE | Train R² | Test R² |
|-------|-------------|-----------|----------|---------|
| Ridge | ~31,832     | ~32,867   | 0.8301   | 0.8592  |
| Lasso | ~31,709     | ~32,638   | 0.8314   | 0.8611  |

✅ Both models generalize well, with minimal overfitting.

---

## 📁 Project Structure

- `House_price_prediction_project.ipynb` — The full Colab notebook.
- `submission.csv` — Final predictions (`Id` + `SalePrice`).

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/house-price-prediction.git
   cd house-price-prediction
