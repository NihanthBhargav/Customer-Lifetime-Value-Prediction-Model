🧮 Customer Lifetime Value (LTV) Prediction
📌 Objective
This project aims to predict the Lifetime Value (LTV) of customers based on historical purchase data. Accurate LTV predictions enable better customer segmentation and targeted marketing strategies.

🛠 Tools & Libraries
Python (pandas, numpy, sklearn, xgboost, matplotlib, seaborn)

Excel (for initial data exploration)

Jupyter Notebook (program.ipynb)

📂 Dataset
customers.csv: Customer ID and demographic info

transactions.csv: Purchase history including date and order value

🔄 Process Overview
1. Data Preprocessing
Merged customers.csv and transactions.csv using CustomerID

Removed nulls, duplicates, and ensured date formatting

2. Feature Engineering
Frequency: Number of purchases per customer

Recency: Days since last purchase

Average Order Value (AOV): Mean order value per customer

3. Modeling
Trained XGBoost Regressor for LTV prediction

Evaluated using:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

4. Segmentation
Classified customers into segments based on predicted LTV (e.g., High, Medium, Low)

📊 Visualization
Included ltv_distribution.png for LTV prediction distribution

Other visual insights available in the Jupyter notebook

📦 Deliverables
program.ipynb: Full code with explanations and outputs

ltv_distribution.png: Visual of predicted LTVs

ltv_predictions.csv: Final LTV predictions per customer

Trained XGBoost model (optional .pkl file)

🚀 Getting Started
Clone repo

Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run program.ipynb step-by-step

Review ltv_predictions.csv for output

📈 Sample Output
| CustomerID | Predicted_LTV |
| ---------- | -------------- |
| 10234      | 1345.78        |
| 10235      | 456.23         |
