# Explainable AI for COVID-19 Mortality Prediction Using Machine Learning Models

This repository contains the implementation and analysis of various machine learning models for predicting COVID-19 mortality, with a strong emphasis on **interpretability** and **explainability** using tools like **SHAP**, **LIME**, **Partial Dependence Plots**, and more.

## 🧠 Project Overview

The goal of this project is to build predictive models that are not only **accurate** but also **transparent**. By leveraging publicly available COVID-19 data, we demonstrate how different models make predictions and how explainable AI (XAI) techniques can help reveal the factors driving those predictions.

### Key Features

- Trained models include:
  - Random Forest
  - XGBoost
  - Histogram-Based Gradient Boosting
  - Logistic Regression
  - Linear Regression
  - Support Vector Classification (SVC)
  - 1D Convolutional Neural Network (CNN)

- Explainability methods applied:
  - SHAP (SHapley Additive exPlanations)
  - LIME (Local Interpretable Model-Agnostic Explanations)
  - PDP (Partial Dependence Plots)
  - ICE (Individual Conditional Expectation)
  - Permutation Feature Importance

## 📊 Dataset

We used a publicly available dataset from [Kaggle](https://www.kaggle.com/imdevskp/covid-19-dataset) containing country-wise COVID-19 statistics. Key features include:

- Confirmed cases
- Deaths
- Recoveries
- Active cases
- Incident and mortality rates

Preprocessing steps included handling missing values, removing irrelevant columns, and normalizing numerical features.

## 🧪 Model Evaluation

Model performance was measured using metrics like:

- **Regression Models**: MAE, RMSE, R²
- **Classification Models**: Accuracy, Precision, Recall, F1 Score

| Model                    | R² Score | RMSE  | Notable Strength                                   |
|--------------------------|----------|--------|----------------------------------------------------|
| XGBoost Regression       | 0.858    | 1.45   | Best overall predictive accuracy                   |
| CNN Regression           | 0.570    | 2.52   | Captures complex temporal patterns                |
| Linear Regression        | 0.435    | 2.91   | High interpretability                              |
| Logistic Regression (Cls)| 0.84 Acc | —      | Solid baseline for severity classification         |

## 🔍 Explainability Highlights

- **SHAP** identified **Case Fatality Rate**, **new deaths**, and **recovery ratios** as major mortality predictors.
- **LIME** offered granular, local instance-level explanations for model predictions.
- **PDP/ICE** illustrated feature impact patterns (e.g., diminishing returns for recovery rates).
- **Permutation Importance** confirmed stability and ranking of key features across models.

## 📁 Repository Structure
├── 3_Models_Abdelaziz_202201827.ipynb # Main Jupyter notebook with code and visualizations
├── Explainable_AI_Report.pdf # Detailed project report and results
├── README.md 

## 🧑‍💻 Authors

- **Abdelaziz ElHelaly Eleisawy**
- **EzzEldeen Ahmad**
- **Salma Khairy**












