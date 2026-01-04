# Credit-Risk-Prediction-Portfolio-Optimization-Explainable-ML
📊 Credit Risk Prediction & Portfolio Optimization (Explainable ML)
🔍 Project Overview

This project implements an end-to-end credit risk prediction system that helps financial institutions assess loan default risk, assign risk categories, and make profit-aware lending decisions using machine learning and explainable AI.

The solution predicts Probability of Default (PD), segments customers into risk buckets, applies risk-based pricing, and estimates expected loss and profit, simulating real-world banking decisions.

🎯 Business Problem

Banks face two major challenges:

1.Minimizing credit losses due to loan defaults

2.Maximizing profitability while maintaining regulatory compliance

Traditional rule-based systems are limited. This project replaces them with a data-driven, explainable ML solution.

🛠️ Tech Stack

--Python

--Pandas, NumPy

--Scikit-learn

--XGBoost

--SHAP (Explainable AI)

--Matplotlib, Seaborn

--Jupyter Notebook

🔄 Project Workflow

1.Data Cleaning & Feature Engineering

2.Exploratory Data Analysis (EDA)

3.Model Training (Logistic Regression, Random Forest, XGBoost)

4.Model Evaluation (Recall, F1-score, ROC-AUC)

5.Explainability using SHAP (Global Feature Importance)

6.Risk Scoring & PD Buckets

7.Loan Approval & Risk-Based Pricing

8.Expected Loss & Profit Simulation

| Model               | Recall (Default) | ROC-AUC   |
| ------------------- | ---------------- | --------- |
| Logistic Regression | ~56%             | —         |
| Random Forest       | ~71%             | —         |
| **XGBoost (Final)** | **~79%**         | **~0.94** |

💡 Key Insights

1.High loan-to-income ratio significantly increases default risk

2.Lower loan grades are strong predictors of default

3.Borrowers with prior defaults are highly risky

4.Risk-based pricing improves portfolio profitability

✅ Final Outcome

The project delivers a production-ready credit risk framework that is:

--Accurate

--Explainable

--Business-aligned

--Regulatory-friendly

Loan Approval & Risk-Based Pricing

Expected Loss & Profit Simulation
