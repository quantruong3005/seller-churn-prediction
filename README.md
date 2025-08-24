# Seller Churn Prediction – Case Study

## 📌 Overview
This project demonstrates the use of **machine learning for churn prediction** 
in a marketplace / e-commerce seller context.  

The goal is to move from reactive monitoring (dashboards showing what already happened) 
to **proactive interventions** that identify at-risk sellers before they disengage.  

- First-of-its-kind churn model (case study demo)  
- Predicts churn **one month in advance** with high confidence  
- Provides **interpretable drivers and thresholds** (e.g., sales momentum, session consistency, cancellations)  
- Delivers actionable insights for account management & retention strategy  

---

## ⚙️ Project Structure
seller-churn-prediction/
│
├── README.md # Project overview (this file)
├── requirements.txt # Dependencies
├── .gitignore # Ignore raw data/models
│
├── data/
│ └── sample/ # Dummy dataset for demo
│
├── notebooks/ # Jupyter notebooks
│ ├── 01_data_prep.ipynb
│ ├── 02_model_train.ipynb
│ └── 03_explainability.ipynb
│
├── src/ # Python scripts
│ ├── data.py
│ ├── train.py
│ ├── evaluate.py
│ └── explain.py
│
├── reports/ # Documentation
│ ├── executive_summary.md
│ ├── results.md
│ └── figures/
│
└── LICENSE

---

## 🧪 Methodology
1. **Data preparation** – Engineered seller activity, sales, and operational features.  
2. **Model training** – Compared Logistic Regression, Random Forest, and LightGBM.  
   - LightGBM chosen for imbalanced dataset handling and explainability.  
3. **Explainability** – SHAP values to identify top churn drivers.  
4. **Risk thresholds** – Derived practical cut-offs for intervention (e.g., sales decline, inactivity).  

---

## 📊 Results (Demo Case)
- Correctly identifies ~**9 out of 10 churners** one month in advance.  
- Balanced performance: Precision ≈ 85%, Recall ≈ 87%, F1 ≈ 0.86.  
- **Top churn drivers**: sales momentum, session consistency, visibility, cancellations.  

---

## 🚀 Key Takeaways
- **Conversion and Activity are the strongest levers** for retention.  
- **Traffic, Operations, Investment** act as enablers, but not standalone fixes.  
- Churn risk increases sharply when multiple signals deteriorate together.  

---

## 📂 Reports
- [Executive Summary](reports/executive_summary.md)  
- [Results](reports/results.md)  

---

## 🔒 Notes on Data
- This repo uses **dummy/public datasets** for demonstration.  
- Original dataset and production model are **proprietary and not included**.  
- To reproduce, you can test with open datasets like [Telco Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn).  

---

## 📝 License
This project is published for **educational and portfolio purposes only**.  
Not intended for commercial use without permission.

---

📌 **Note:** This project is shared as a case study for learning and demonstration.  
Please see the [LICENSE](LICENSE) file for details.
