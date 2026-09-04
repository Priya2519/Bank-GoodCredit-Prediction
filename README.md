# Bank-GoodCredit-Prediction
End-to-End Predictive Risk Modeling: Built a Credit Risk Scoring Model for Bank GoodCredit to identify high-risk credit card customers likely to fall into the 30+ Days Past Due (DPD) bucket, successfully mitigating credit default risk.  Eliminated low-signal attributes and analyzed key data signals (e.g., outstanding debt, past due amounts)
## 📌 Project Overview

This project focuses on predicting customer credit risk using Machine Learning classification techniques.

The objective is to identify customers who are more likely to exhibit risky credit behavior and support data-driven credit risk assessment.

The project covers the complete Machine Learning workflow, including data extraction, exploratory data analysis, data preprocessing, feature engineering, model development, model evaluation, feature importance analysis, and risk segmentation.

---

## 🎯 Business Objective

The primary objective is to develop a Machine Learning model that can identify customers with higher credit risk.

The analysis aims to:

- Understand customer credit and financial behavior
- Identify important factors associated with credit risk
- Perform data cleaning and preprocessing
- Engineer meaningful predictive features
- Train and evaluate Machine Learning classification models
- Analyze feature importance
- Segment customers based on predicted risk
- Generate business-oriented insights for credit risk management

---

## 📊 Dataset

The project uses customer-level banking and credit-related data.

Dataset characteristics:

- Approximately 40,000 customer records
- Multiple customer demographic, financial, and credit-related variables
- Target variable: `Bad_label`

The dataset contains sensitive/customer information and is therefore **not included in this public repository**.

---

## 🔎 Exploratory Data Analysis

The project performs exploratory analysis to understand:

- Customer characteristics
- Distribution of financial variables
- Missing values
- Outliers
- Class imbalance
- Customer tenure/vintage
- Credit utilization behavior
- Credit-seeking behavior
- Relationships between variables and credit risk

---

## ⚙️ Data Preprocessing

The preprocessing workflow includes:

- Missing-value treatment
- Data cleaning
- Handling categorical variables
- Numerical feature preprocessing
- Outlier analysis
- Feature transformation where required
- Preparation of data for Machine Learning

---

## 🛠️ Feature Engineering

Relevant predictive features are created and analyzed to improve model performance.

Examples include credit utilization-related measures and other customer behavioral and financial indicators.

Feature engineering focuses on extracting meaningful signals from the available customer data.

---

## 🤖 Machine Learning

The project applies Machine Learning classification techniques to predict customer credit risk.

The workflow includes:

1. Preparing the modeling dataset
2. Splitting data into training and testing sets
3. Training classification models
4. Generating predictions
5. Evaluating model performance
6. Comparing model results
7. Analyzing important predictive features

---

## 📈 Model Evaluation

Model performance is evaluated using appropriate classification and ranking metrics.

Key evaluation areas include:

- Classification performance
- Ranking performance
- Gini coefficient
- Model discrimination
- Prediction quality

The project achieved a Gini benchmark of approximately **37.9**.

---

## 💡 Business Insights

The analysis provides insights into factors associated with customer credit risk, including:

- Customer tenure/vintage
- Credit utilization behavior
- Financial characteristics
- Credit-seeking behavior
- Distribution of risky and non-risky customers
