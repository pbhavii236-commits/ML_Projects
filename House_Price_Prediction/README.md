# 🏠 House Price Prediction — Regression

A machine learning project to predict California housing prices using multiple regression models.

---

## 📌 Project Overview

This project uses the California Housing dataset to build and compare multiple regression models, identifying key factors that influence housing prices.

---

## 📁 Dataset

- **Name:** California Housing Dataset  
- **Source:** [california_housing.csv]  
- **Records:** 20,640 samples  
- **Features:** 8 numerical features  
- **Target:** Median house value  

---

## 🔧 Libraries Used

- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

---

## 🚀 Project Workflow

1. Data loading  
2. EDA & correlation analysis  
3. Feature engineering & scaling  
4. Model training (Linear, Ridge, RF, GB)  
5. Model evaluation (MAE, RMSE, R²)  
6. Best model analysis  

---

## 📊 Model Performance Summary

| Model | R² Score |
|------|--------|
| **Gradient Boosting** | **0.83** |
| Random Forest | 0.80 |
| Linear Regression | 0.56 |
| Ridge Regression | 0.56 |

> ✅ **Best Model: Gradient Boosting — R² = 0.83**

---

## 🔍 Key Insights

- Median Income is the strongest predictor  
- Tree-based models outperform linear models  
- Location features significantly impact price  
- Feature engineering improves performance  

---

## 📌 Conclusion

Ensemble models like Gradient Boosting provide the most accurate predictions for housing prices.

---

## 🚀 Future Improvements

- Hyperparameter tuning  
- Try XGBoost  
- Deploy using Streamlit  

---

## ▶️ How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook house_price.ipynb
