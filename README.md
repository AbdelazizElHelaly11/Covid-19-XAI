Explainable AI for COVID-19 Mortality Prediction Using Machine Learning Models
📘 Overview
This project applies machine learning techniques to predict COVID-19 mortality rates and leverages Explainable AI (XAI) methods to interpret the models' predictions. Our goal is not only to build accurate models but also to ensure transparency and trust in their outputs, especially for high-stakes applications like public health forecasting.

Using a dataset from Kaggle — "COVID-19 Dataset – Country-wise Latest" — we preprocess and analyze key features such as confirmed cases, recoveries, incident rates, and more. We train several machine learning models and apply SHAP (SHapley Additive exPlanations) to interpret the influence of each feature on predicted mortality rates.

🔍 Research Questions
What are the most influential features in predicting COVID-19 mortality rates across countries?

How effective is SHAP in explaining model predictions?

How can interpretability foster trust and reliability in public health AI systems?

💡 Key Features
Multiple ML models: Random Forest, XGBoost, Histogram-based Gradient Boosting, Logistic Regression, Linear Regression, SVC

Feature importance analysis via SHAP

Detailed visualizations of global and regional COVID-19 patterns

Performance metrics: MAE, RMSE, R²

🛠️ Methodology
1. Data Preprocessing
Removed irrelevant fields

Normalized numerical values

Handled missing entries

Train-test split applied

2. Exploratory Data Analysis (EDA)
Trend analysis of global and country-specific cases, deaths, and recoveries

Infection rate visualizations per million

Regional comparisons of mortality and recovery rates

Correlation analysis (e.g., Population density vs. infection rate)

3. Modeling & Evaluation
Trained multiple regression-based models

Evaluated using:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R-squared (R²)

4. Explainability
Applied SHAP to explain predictions

Identified top contributing features per model

Compared global vs regional model behavior

📁 Dataset
Source: Kaggle COVID-19 Dataset – Country-wise Latest

Columns used: Confirmed, Deaths, Recovered, Active, Incident Rate, Mortality Rate

📷 Visualizations
The repository includes plots demonstrating:

Daily/weekly growth rates

Case fatality ratios

Recovery vs. active case dynamics

Continental and regional disparities

Population density correlations

🧠 Explainable AI Techniques
SHAP (SHapley Additive exPlanations): Main tool for feature attribution

Potential for further integration: LIME, Grad-CAM (not yet implemented)

🤝 Contributors
Abdelaziz ElHelaly Eleisawy

EzzEldeen Ahmad

Salma Khairy
Faculty of Computational Sciences and Artificial Intelligence, Zewail City
