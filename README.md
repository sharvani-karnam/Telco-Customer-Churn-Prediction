# 🔮 Telco Customer Churn Prediction

A Machine Learning project that predicts whether a customer will leave a telecommunications service provider. This project covers the full Data Science pipeline: data extraction from SQL, preprocessing, model training, and visualization.

## 📊 Project Overview
* **Goal:** Predict customer churn (Yes/No) based on billing and usage patterns.
* **Algorithm:** Random Forest Classifier.
* **Accuracy Achieved:** ~79.5%.
* **Tech Stack:** Python, Pandas, MySQL, Scikit-Learn, Seaborn.

## ⚙️ How It Works
1.  **Database Connection:** The system connects to a local MySQL database to fetch raw customer data.
2.  **Preprocessing:** Handles missing values and encodes categorical variables (turning text like "Yes/No" into 0/1).
3.  **Training:** Uses a **Random Forest Classifier** (100 estimators) to learn patterns from the data.
4.  **Prediction:** Can take new customer data (Monthly Bill, Tenure, etc.) and calculate the probability of them leaving.

## 📈 Key Insights
* **Top Risk Factors:** High `MonthlyCharges` and low `tenure` are the biggest indicators of churn.
* **Visualizations:** Includes charts for Feature Importance and Density plots for churn distribution.

## 🚀 How to Run
1.  Import the `telco_churn.csv` into your MySQL database.
2.  Update the database credentials in the notebook.
3.  Run the Jupyter Notebook cells sequentially.

---
*Created by Sharvani Karnam - B.Tech AIML student*
