# End-to-End Telco Customer Churn Prediction & Business Impact Analysis

## Project Overview
Customer churn is one of the most critical business metrics for subscription-based companies. This project builds a complete end-to-end Machine Learning classification pipeline to predict whether a telecommunications customer will churn based on demographic data, account information, and service subscriptions. 

Beyond raw model accuracy, this project identifies the key drivers of customer attrition to help business stakeholders implement targeted retention strategies.

---

## Tech Stack & Libraries
* Language: Python 3.x
* Environment: Google Colab
* Data Manipulation & Cleaning: Pandas, NumPy
* Data Visualization: Seaborn, Matplotlib
* Machine Learning & Preprocessing: Scikit-learn (Logistic Regression, Random Forest, StandardScaler, Train-Test Split)

---

## Key Exploratory Data Analysis (EDA) Insights
1. Class Imbalance: Approximately 26.5% of customers in the dataset churned, requiring careful evaluation of metrics beyond simple accuracy (focusing on Precision, Recall, and F1-Score).
2. Contract Vulnerability: Customers on Month-to-month contracts exhibit a drastically higher churn rate compared to those locked into 1-year or 2-year agreements.

---

## Model Performance & Evaluation
Two classification models were trained and evaluated on an 80/20 stratified test split:
* Logistic Regression: Achieved ~80.5% overall accuracy with balanced precision and recall.
* Random Forest Classifier: Successfully captured non-linear relationships among customer charges and tenure length.

### Top Churn Drivers (Feature Importance):
* TotalCharges & MonthlyCharges
* Customer tenure (Newer customers are at highest risk)
* Contract_Month-to-month status

---

## How to Run This Project Locally or in Colab
1. Clone the repository:
   ```bash
   git clone [https://github.com/malakmagam-ops/telco-customer-churn-prediction.git](https://github.com/malakmagam-ops/telco-customer-churn-prediction.git)
