# Telecom Customer Churn Prediction & Retention Analytics

## Project Overview

Customer churn is one of the biggest challenges faced by telecom companies. Acquiring new customers is significantly more expensive than retaining existing ones. This project focuses on predicting customer churn using Machine Learning and identifying key factors influencing customer retention.

The project combines Data Analysis, Feature Engineering, Machine Learning, and Power BI Dashboarding to provide actionable insights that help businesses reduce customer attrition and improve retention strategies.

---

## Business Problem

Telecom companies often struggle to identify customers who are likely to leave their services.

The objective of this project is to:

* Predict customer churn using Machine Learning.
* Identify key factors contributing to churn.
* Analyze customer behavior and retention patterns.
* Develop an interactive Power BI dashboard for business decision-making.

---

## Dataset

**Dataset:** Telco Customer Churn Dataset

### Dataset Information

* Total Customers: 7,043
* Features: 21
* Target Variable: Churn

### Key Features

* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure
* Phone Service
* Internet Service
* Contract Type
* Payment Method
* Monthly Charges
* Total Charges
* Churn

---

## Technologies Used

### Programming & Analysis

* Python
* Pandas
* NumPy

### Machine Learning

* Scikit-Learn
* XGBoost
* Logistic Regression
* Random Forest Classifier

### Visualization

* Matplotlib
* Seaborn
* Power BI

### Development Environment

* Google Colab

---

## Project Workflow

### 1. Data Cleaning

* Handled missing values
* Converted TotalCharges to numeric format
* Removed invalid records
* Verified data consistency

### 2. Exploratory Data Analysis (EDA)

Analyzed:

* Customer churn distribution
* Contract type impact on churn
* Internet service impact on churn
* Payment method behavior
* Monthly charges vs churn
* Tenure vs churn

### 3. Feature Engineering

* One-Hot Encoding of categorical variables
* Feature scaling using StandardScaler
* Preparation of model-ready datasets

### 4. Machine Learning Models

Three models were evaluated:

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 80.38%   |
| Random Forest       | 78.68%   |
| XGBoost             | 77.83%   |

### Final Model

**Logistic Regression**

Selected because it achieved the highest accuracy and demonstrated strong generalization performance.

---

## Key Findings

* Month-to-month contract customers showed the highest churn rates.
* Customers with shorter tenure were more likely to leave.
* Higher monthly charges were associated with increased churn.
* Contract type and tenure were among the strongest churn indicators.
* Logistic Regression outperformed Random Forest and XGBoost on this dataset.

---

## Power BI Dashboard

### Page 1 – Executive Overview

KPIs:

* Total Customers
* Churned Customers
* Average Monthly Charges
* Average Tenure

Visualizations:

* Churn Distribution
* Contract Distribution
* Internet Service Distribution
* Monthly Charges Analysis

---

### Page 2 – Churn Analysis

Visualizations:

* Contract Type vs Churn
* Internet Service vs Churn
* Payment Method vs Churn
* Monthly Charges vs Churn
* Tenure vs Churn

---

### Page 3 – Churn Prediction Dashboard

Visualizations:

* Model Comparison
* Feature Importance
* Predicted Churn Distribution
* Prediction Results

---

## Repository Structure

```text
Telecom-Customer-Churn-Prediction-and-Retention-Analytics/

│
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── Telecom_Customer_Churn_Prediction.pbix
├── Telecom_Churn_Analysis.ipynb
├── feature_importance.csv
├── model_comparison.csv
├── churn_predictions.csv
│
├── screenshots/
│   ├── executive_overview.png
│   ├── churn_analysis.png
│   └── churn_prediction_dashboard.png
│
└── README.md
```

## Business Recommendations

* Encourage customers to switch from month-to-month contracts to long-term plans.
* Introduce loyalty programs for customers with low tenure.
* Offer personalized retention campaigns for high-risk customers.
* Monitor customers with high monthly charges and low engagement.

---

## Future Improvements

* Hyperparameter tuning
* Advanced ensemble models
* Real-time churn prediction
* Streamlit deployment
* SQL database integration
* Cloud deployment

---

## Author

**Tanishq Belhekar**

B.Sc. Data Science & Big Data Analytics

GitHub: Tanishq0909
## Dashboard Screenshots

### Executive Overview

![Executive Overview](screenshots/executive_overview.png)

### Churn Analysis

![Churn Analysis](screenshots/churn_analysis.png)

### Churn Prediction Dashboard

![Churn Prediction Dashboard](screenshots/churn_prediction_dashboard.png)
