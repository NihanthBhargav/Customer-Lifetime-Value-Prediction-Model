# 🧮 Customer Lifetime Value (LTV) Prediction

## 📌 Objective
Predict the Lifetime Value (LTV) of customers using historical purchase data.  
This helps in customer segmentation and enables targeted marketing strategies.

---

## 🛠 Tools & Libraries
- **Python**: `pandas`, `numpy`, `sklearn`, `xgboost`, `matplotlib`, `seaborn`
- **Excel**: Initial data exploration
- **Jupyter Notebook**: `program.ipynb`

---

## 📂 Dataset
- `customers.csv`: Customer ID and demographic information
- `transactions.csv`: Purchase history including date and order value

---

## 🔄 Workflow

### 🔹 1. Data Preprocessing
- Merged `customers.csv` and `transactions.csv`
- Cleaned nulls and duplicates
- Formatted date fields properly

### 🔹 2. Feature Engineering
- **Frequency**: Number of purchases per customer  
- **Recency**: Days since the last purchase  
- **AOV**: Average Order Value per customer

### 🔹 3. Modeling
- Used **XGBoost Regressor** for LTV prediction
- Evaluation Metrics:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)

### 🔹 4. Customer Segmentation
Based on predicted LTV:
- High Value
- Medium Value
- Low Value

---

## 📊 Visualizations
- `ltv_distribution.png`: Distribution of predicted LTVs  
- Additional plots are included in `program.ipynb`

---

## 📦 Deliverables
- `program.ipynb`: Full code with explanations and outputs  
- `ltv_distribution.png`: LTV prediction visualization  
- `ltv_predictions.csv`: Final predicted LTV values  
- `model.pkl`: Trained XGBoost model (optional)

---
