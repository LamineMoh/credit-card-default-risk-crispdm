# Credit Card Default Risk Prediction (CRISP-DM)

## 📌 Project Overview
This project aims to predict credit card default risk using a structured **CRISP-DM methodology**.
It focuses on balancing **model performance** and **business impact**, with a particular emphasis on
**cost-sensitive evaluation**, which is critical in financial risk management.

## 🏦 Business Problem
Credit card default represents a significant financial risk for banks and financial institutions.
The objective is to identify clients likely to default on their next payment in order to:
- Reduce financial losses
- Improve credit decision-making
- Support risk management strategies

## 🎯 Business Objective
Predict whether a client will default on their next credit card payment while minimizing
**false negatives**, which represent the most costly business error.

## 📊 Dataset
- Source: Public credit card default dataset
- Size: ~30,000 clients
- Target variable: `default.payment.next.month`
- Features include credit limit, payment history, bill amounts, and demographic information

## 🔍 Methodology (CRISP-DM)

### 1. Business Understanding
- Defined business objectives and success criteria
- Identified cost asymmetry between prediction errors

### 2. Data Understanding
- Exploratory Data Analysis (EDA)
- Distribution analysis, class imbalance, and bivariate relationships

### 3. Data Preparation
- Data cleaning and validation
- Feature engineering based on payment behavior and credit utilization
- Creation of processed datasets for modeling

### 4. Modeling
- Baseline Logistic Regression (interpretable model)
- Threshold tuning to improve recall
- Comparison with tree-based models:
  - Random Forest
  - Gradient Boosting

### 5. Evaluation
- Metrics: Recall, Precision, Confusion Matrix
- Cost-sensitive evaluation to quantify business impact
- Trade-off analysis between performance and interpretability

## 📈 Key Results
- Improved recall by adjusting the decision threshold
- Significant reduction in estimated business cost
- Tree-based models captured non-linear patterns but reduced interpretability
- Logistic Regression retained for its balance between performance and explainability

## 🧠 Key Learnings
- Accuracy alone is not sufficient for imbalanced financial datasets
- Business-driven metrics are essential in credit risk modeling
- Model evaluation must align with real-world financial impact

## 🛠️ Technologies & Tools
- Python, Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook
- Git & GitHub

## 📁 Project Structure
## 🚀 Next Steps
- Hyperparameter optimization to further improve recall and stability
- Advanced cost-sensitive optimization based on business constraints
- Model monitoring and performance tracking considerations for production


