# Telecom Customer Churn Prediction & Analytics

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Framework](https://img.shields.io/badge/Scikit--Learn-Latest-orange.svg)](https://scikit-learn.org/)
[![Visualization](https://img.shields.io/badge/Power%20BI-Dashboard-yellow.svg)]()

## 📌 Project Overview
In the highly competitive telecommunications industry, retaining existing customers is significantly more cost-effective than acquiring new ones. This project focuses on analyzing customer demographics, account characteristics, and service usage to predict customer churn attrition and identify key drivers behind customer departures.

The end goal is to provide actionable, data-driven insights that empower retention teams to proactively engage high-risk customer segments.

## 📊 Key Insights & Business Impact
* **Contract Risk:** Customers on **Month-to-Month contracts** exhibit a disproportionately higher churn rate compared to one or two-year contracts.
* **Service Vulnerabilities:** Fiber optic internet subscribers show higher attrition patterns, suggesting potential pricing or technical stability pain points.
* **Financial Impact:** (Optional: Insert a specific metric here, e.g., "The model successfully flags X% of churned revenue, allowing targeted save-offers.")

*(Optional: Insert a screenshot of your Power BI dashboard or a key Seaborn/Plotly chart here)*

## 🛠️ Tech Stack & Methodology
* **Data Manipulation:** Pandas, NumPy
* **Exploratory Data Analysis (EDA):** Matplotlib, Seaborn, Power BI (for interactive visual tracking)
* **Machine Learning Pipelines:** Scikit-Learn (Logistic Regression, Random Forest, XGBoost)
* **Imbalance Handling:** SMOTE / Class Weight adjustments
* **Model Evaluation:** Precision, Recall, F1-Score, and ROC-AUC

## 🚀 Steps in Project Execution

### 1. Data Cleaning & Preprocessing
* Handled missing or incorrectly formatted values (such as transforming `TotalCharges` to numeric).
* Encoded categorical features using One-Hot/Ordinal Encoding.
* Scaled numeric variables (`Tenure`, `MonthlyCharges`) to optimize model convergence.

### 2. Exploratory Data Analysis (EDA)
* Analyzed relationships between churn rates and billing methods, contract structures, and tenure distribution.
* Created a clean Star Schema model for interactive data slicing.

### 3. Predictive Modeling & Evaluation
* Developed baseline classification models.
* Tuned hyperparameters to optimize for **Recall**—minimizing false negatives ensuring we miss fewer customers at risk of leaving.

## 📁 Repository Structure
```text
├── Data/                             # Dataset or links to source files
├── Notebooks/
│   └── Telecom Customer Churn Prediction.ipynb  # Primary exploration and modeling code
├── Dashboards/                       # Power BI .pbix file or exported views
├── README.md                         # Project documentation
└── requirements.txt                  # Python dependencies
