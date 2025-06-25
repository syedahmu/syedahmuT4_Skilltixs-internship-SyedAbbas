# Telco Customer churn analysis :
📊 Telecom Customer Churn Prediction
Overview
A data science project to predict customer churn in the telecom industry using machine learning. By analyzing customer demographics, subscription patterns, and usage behavior, this project builds models to identify which customers are most at risk of leaving the service.

🎯 Objective
Develop a reliable churn prediction model that helps telecom providers:

Proactively identify at-risk customers

Understand key factors driving churn

Improve customer retention strategies

🔧 Tools
Python: pandas, numpy, matplotlib, seaborn

Modeling: scikit-learn (Logistic Regression, Random Forest)

Preprocessing: LabelEncoder, OneHotEncoder, StandardScaler

Saving the model: joblib/pickle

🧪 Key Steps
Exploratory Data Analysis (EDA):

Visualized churn distribution and correlations

Identified important numeric vs categorical features

Data Preprocessing:

Handled missing/erroneous values (e.g., TotalCharges)

Encoded binary and multi-class categorical features

Scaled numeric features for model readiness

Model Training & Evaluation:

Logistic Regression as baseline

Random Forest for improved performance

Hyperparameter tuning, ROC‑AUC, Precision/Recall evaluation

Visualized feature importances to highlight churn predictors

Model Persistence:

Saved best-performing model using joblib for future deployment

📈 Results
The Random Forest model achieved strong performance with an ROC‑AUC of your metric here

Top predictors of churn included monthly charges, contract type, tenure, and service features

📂 Repository Contents
Telco_Churn_Prediction.ipynb: full Jupyter notebook

rf_churn_model.pkl: serialized Random Forest

requirements.txt: list of dependencies

🔄 How to Use
Clone the repo

Install dependencies via pip install -r requirements.txt

Open and run the notebook to reproduce EDA and modeling

Use the serialized model to predict churn on new customer data


🌟 Why This Matters
Customer churn is expensive—retaining existing subscribers saves far more than acquiring new ones. This project provides a production-ready foundation for telecom companies to protect their revenue by identifying and acting on at-risk customers.


