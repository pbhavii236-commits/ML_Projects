# 🤖 Machine Learning Portfolio

End-to-end Machine Learning projects demonstrating **Data Analysis, Regression, and Classification** skills.

---

## 📁 Projects

### 🚢 1. EDA on Titanic Dataset
**Skills:** Pandas, Seaborn, Matplotlib, Feature Engineering  

- **Problem:** Titanic passengers mein survival patterns analyze karna  
- **Dataset:** 891 passengers, 12 features (Kaggle Titanic)  
- **Key Findings:**  
  - Females survival rate: **74%**  
  - Males survival rate: **19%**  
  - Passenger class strong factor tha  
- **Output:** 20+ visualizations, cleaned dataset, 6 insights  

👉 📓 Notebook: `EDA_Titanic.ipynb`

---

### 🏠 2. House Price Prediction
**Skills:** Linear Regression, Ridge, Lasso, Gradient Boosting, Scikit-learn  

- **Problem:** House prices predict karna  
- **Dataset:** 20,640 records (California Housing)  
- **Best Model:** Gradient Boosting → **R² = 0.83**  
- **Key Learning:** Log transformation + location features improve accuracy  

👉 📓 Notebook: `House_Price_Prediction.ipynb`

---

### 📉 3. Customer Churn Prediction
**Skills:** Random Forest, ROC-AUC, Confusion Matrix, Business Analysis  

- **Problem:** Customer churn predict karna  
- **Dataset:** 7,043 customers (IBM Telco)  
- **Best Model:** Random Forest  
  - Accuracy: **80%**  
  - ROC-AUC: **0.85**  
- **Business Insight:** Month-to-month users high churn risk  

👉 📓 Notebook: `Customer_Churn_Classification.ipynb`

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **ML:** Scikit-learn  
- **Models:** Linear, Ridge, Lasso, Random Forest, Gradient Boosting  
- **Metrics:** R², MAE, RMSE, Accuracy, F1, ROC-AUC  

---

## 🚀 How to Run

```bash
# Clone repo
git clone https://github.com/pbhavii236-commits/ML_Projects.git
# Open folder
cd ML_Projects

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# Run notebook
jupyter notebook
