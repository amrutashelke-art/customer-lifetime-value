# 🧠 Customer Lifetime Value (LTV) Prediction Model

## 📌 Objective

To build a machine learning model that predicts the *Lifetime Value (LTV)* of customers based on their past purchase behavior. The goal is to support *targeted marketing strategies* by segmenting customers into high, mid, and low value groups.

---

## 🧰 Tools & Technologies

- 🐍 Python (Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn)
- 📊 Excel (for data exploration)
- 📓 Jupyter Notebook
- 🧠 XGBoost for regression modeling
- 💾 Joblib for model serialization

---

## 🔄 Workflow / Steps Involved

1. *Data Preprocessing*
   - Merged transactions with Customer IDs
   - Handled missing and duplicate records
   - Converted date columns to datetime format

2. *Feature Engineering*
   - Recency: Days since last purchase
   - Frequency: Total number of purchases
   - Monetary: Total spend
   - AOV: Average Order Value (Monetary / Frequency)
   - Tenure (First to Last Purchase)

3. *Model Building*
   - Used XGBoost Regressor to predict LTV
   - Evaluated with *MAE* and *RMSE*
   - Visualized feature importance

4. *Customer Segmentation*
   - Segmented customers into:
     - High Value
     - Mid Value
     - Low Value

---

## 📈 Model Performance

| Metric | Value     |
|--------|-----------|
| MAE    | ~45.56    |
| RMSE   | ~55.88    |

---

## 📂 Deliverables

- ✅ LTV_Prediction_Model.ipynb – End-to-end project notebook
- ✅ xgboost_ltv_model.pkl – Trained ML model
- ✅ ltv_predictions.csv – CSV file with actual & predicted LTV
- ✅ feature_importance.png – Visual showing top features
- ✅ Customer_LTV_Prediction_Report.pdf – 2-page professional report

---
