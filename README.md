# Telco_Customer_Churn_Data
The Telco Customer Churn dataset contains information about customers of a telecommunications company and whether they have discontinued the service (churned) or not. It is widely used for classification tasks, customer retention analysis, and predictive modeling.

 📞 Telco Customer Churn Prediction Using Machine Learning  
### AI-Powered Customer Retention Prediction System  

This project predicts whether a customer will *churn (leave)* or *stay* with a telecom company using multiple Machine Learning models.  
The system provides *data analysis, model building, feature engineering, evaluation, and deployment* of a churn prediction tool.

---

 🧠 **Project Overview  **
Customer churn affects the revenue and growth of telecom companies.  
This project uses the *IBM Telco Customer Churn Dataset* to identify patterns that influence churn behaviour.

The pipeline includes:

- Exploratory Data Analysis (EDA)
- Feature Engineering (Scaling, Encoding, Imputation, Transformation)
- Training ML models (Logistic Regression, Decision Tree, Random Forest, XGBoost)
- Model comparison using metrics (Accuracy, Recall, F1-score, ROC-AUC)
- Deployment as an interactive dashboard

---

 📂 Dataset Description  
- *Rows:* 7043  
- *Columns:* 21  
- Includes:
  - Customer demographics  
  - Contract details  
  - Billing information  
  - Internet/phone service usage  
  - Churn label (Yes/No)

Dataset preprocessing steps include:
- Removing unnecessary column (customerID)
- Encoding categorical variables
- Handling missing values using KNN, Random Sampling, Iterative Imputation
- Scaling numerical features using StandardScaler
- Variable transformation using Quantile Transformer, Log, Power Transform

---

 🔧 Technologies Used  
- *Python*
- *Pandas, NumPy*
- *Matplotlib, Seaborn*
- *Scikit-learn*
- *XGBoost*
- *SHAP* (Model Explainability)
- *Flask / Streamlit* (Deployment Dashboard)

---

 🔍 Algorithms Used  
 1. Logistic Regression  
- Baseline model  
- Interpretable weights  
- Accuracy: *81.2%*

 2. Decision Tree  
- Simple, rule-based model  
- Accuracy: *83.6%*

 3. Random Forest  
- Ensemble of trees  
- Handles non-linearity  
- Accuracy: *86.5%*

4. XGBoost (Best Model)  
- Gradient boosting algorithm  
- Excellent classification performance  
- *Accuracy: 88.2%*  
- *ROC-AUC: 0.91*

---

## 📊 Model Performance Summary

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|-------|----------|-----------|--------|----------|---------|
| Logistic Regression | 81.2% | 0.79 | 0.77 | 0.78 | 0.84 |
| Decision Tree | 83.6% | 0.81 | 0.80 | 0.81 | 0.85 |
| Random Forest | 86.5% | 0.84 | 0.83 | 0.84 | 0.89 |
| *XGBoost* | *88.2%* | *0.86* | *0.85* | *0.86* | *0.91* |

---

##  Key Insights from Analysis  
- *Month-to-month contracts* → highest churn  
- *High monthly charges* → higher churn risk  
- *Electronic check payment* → highest churn group  
- *Tenure below 12 months* → 47% churn  
- *Long-term contract customers* → more loyal  
- *Auto-payment methods* → reduce churn  
- *Add-on services* (TechSupport, Security) → lower churn  

---

##  Dashboard / Deployment  
A simple UI allows users to input customer details and predict churn instantly.

Example features:
- Tenure  
- Contract type  
- Payment method  
- Total & monthly charges  
- Internet service details  

---


