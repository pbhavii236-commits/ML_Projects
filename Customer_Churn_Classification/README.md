# 📉 Customer Churn Prediction — Classification

A machine learning project to predict customer churn using multiple classification models on the Telco Customer Churn dataset.

---

## 📌 Project Overview

Customer churn is one of the biggest challenges for telecom companies. This project builds and compares multiple ML classification models to predict whether a customer will churn, and identifies the key factors driving churn behavior.

---

## 📁 Dataset

- **Name:** Telco Customer Churn
- **Source:** [Telco-Customer-Churn.csv]
- **Records:** 7,043 customers
- **Features:** 21 columns including tenure, contract type, monthly charges, internet service, etc.
- **Target:** `Churn` (Yes / No)

---

## 🔧 Libraries Used

| Library | Purpose |
|---|---|
| `pandas` | Data loading & manipulation |
| `numpy` | Numerical operations |
| `matplotlib` | Data visualization |
| `seaborn` | Statistical plots |
| `scikit-learn` | ML models & evaluation |

---

## 🚀 Project Workflow

1. **Load Dataset** — Telco Customer Churn CSV
2. **Data Preprocessing** — Handle missing values, encode categorical features
3. **EDA** — Explore churn patterns across features
4. **Feature Engineering** — Scale and transform features
5. **Model Training** — Train multiple classifiers
6. **Evaluation** — Compare models using Accuracy, F1-Score, ROC-AUC
7. **Business Impact Analysis** — Identify actionable churn drivers
8. **Conclusions** — Key findings and future improvements

---

## 📊 Model Performance Summary

| Model | Accuracy | F1-Score | ROC-AUC |
|---|---|---|---|
| **Random Forest** | ~80% | ~0.61 | ~0.85 |
| **Gradient Boosting** | ~80% | ~0.61 | ~0.84 |
| **Logistic Regression** | ~80% | ~0.59 | ~0.84 |
| **Decision Tree** | ~78% | ~0.55 | ~0.74 |

> ✅ **Best Model: Random Forest** — highest ROC-AUC of ~0.85

---

## 🔍 Key Churn Drivers

1. **Contract Type** — Month-to-month customers have highest churn risk
2. **Tenure** — New customers (< 12 months) are more likely to churn
3. **Monthly Charges** — Higher charges increase churn probability
4. **Internet Service** — Fiber optic users show higher churn vs DSL

---

## 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Handle class imbalance using SMOTE
- Deploy model using Flask or Streamlit

---

## ▶️ How to Run

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open the notebook:
   ```bash
   jupyter notebook Customer_Churn_Classification.ipynb
   ```
## 📊 Output

See full analysis with visualizations in the notebook:
👉 Customer_Churn_Classification.ipynb
---

## 👩‍💻 Author

**Bhavini Patel**  
[GitHub Profile](https://github.com/BhaviniPatel)
