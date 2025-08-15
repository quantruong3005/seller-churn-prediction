# 🛒 Seller Churn Prediction

Churn prediction model for TikTokShop sellers using Python, XGBoost, and SHAP. The project focuses on identifying early signals of seller disengagement to support retention strategies.

## 📊 Methods

- **Preprocessing**: Scaling, encoding, handling missing values  
- **Models**: Logistic Regression, Random Forest, XGBoost  
- **Evaluation**: F1-score, ROC-AUC, Confusion Matrix  
- **Interpretability**: SHAP values for feature importance

## 🔍 Key Results

- **Best model**: XGBoost (F1 = 0.78, AUC = 0.85)  
- **Top predictors**: Declining livestream frequency, drops in bi-weekly activity  
- SHAP analysis provided actionable business insights for retention strategy

## 📁 Structure

- `churn_model.ipynb`: Main notebook  
- `requirements.txt`: Dependencies  
- `plots/`: Model visualizations and SHAP outputs  
- `README.md`: Project summary

Project by Quan Truong | [LinkedIn](https://www.linkedin.com/in/quantruong3005) | [Email](mailto:quan.truong3005@gmail.com)
