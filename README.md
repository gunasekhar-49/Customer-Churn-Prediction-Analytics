# Customer Churn Prediction Analytics

An end-to-end **Customer Churn Prediction and Analytics** project combining **SQL, Python, Machine Learning, and Power BI** to analyze customer churn and predict customers who are likely to leave.

---

## 📌 Project Overview

Customer churn is an important business problem because losing existing customers can reduce revenue and increase customer acquisition costs.

This project builds an end-to-end solution that analyzes customer behavior, predicts potential churners using Machine Learning, and presents the results through an interactive Power BI dashboard.

### Objectives

* Analyze customer churn patterns
* Clean and transform customer data
* Use SQL for data preparation and analysis
* Build a Machine Learning model for churn prediction
* Identify customers predicted to churn
* Analyze predicted churners by different customer attributes
* Build an interactive Power BI dashboard
* Generate insights that can support customer retention strategies

---

## 🛠️ Technologies Used

| Technology           | Purpose                                 |
| -------------------- | --------------------------------------- |
| **Python**           | Data preprocessing and Machine Learning |
| **Pandas**           | Data manipulation and analysis          |
| **Scikit-learn**     | Machine Learning                        |
| **Random Forest**    | Customer churn prediction               |
| **SQL**              | Data preparation and analysis           |
| **Power BI**         | Interactive dashboard and visualization |
| **Jupyter Notebook** | Model development and experimentation   |

---

## 🔄 Project Workflow

```text
Customer Data
      ↓
SQL Data Preparation
      ↓
Python Data Cleaning
      ↓
Feature Encoding
      ↓
Random Forest Model
      ↓
Customer Churn Prediction
      ↓
Predictions.csv
      ↓
Power BI Dashboard
      ↓
Business Insights
```

---

## 🤖 Machine Learning

A **Random Forest Classifier** is used to predict whether a customer is likely to churn.

### Machine Learning Process

1. Load customer data
2. Clean and preprocess the data
3. Handle categorical variables
4. Encode categorical features
5. Prepare model features
6. Train the Random Forest model
7. Generate customer-level predictions
8. Identify predicted churners
9. Export predictions to `Predictions.csv`
10. Analyze predictions using Power BI

---

## 📊 Power BI Dashboard

The Power BI report contains two main dashboard pages.

### 1. Churn Analysis – Summary

The summary dashboard provides an overview of customer churn and customer behavior.

It includes analysis of:

* Total Customers
* New Customers
* Total Churn
* Churn Rate
* Churn by Gender
* Churn by Age Group
* Churn by State
* Churn by Contract
* Churn by Payment Method
* Churn by Tenure
* Churn by Internet Type
* Churn Categories
* Customer Services

### 2. Churn Analysis – Prediction

The prediction dashboard focuses on customers predicted to churn by the Machine Learning model.

It includes:

* Predicted Churner Count
* Predicted Churners by Gender
* Predicted Churners by Age Group
* Predicted Churners by Marital Status
* Predicted Churners by Tenure
* Predicted Churners by State
* Predicted Churners by Payment Method
* Predicted Churners by Contract
* Customer-level prediction details

---

## 🖼️ Dashboard Screenshots

### Churn Analysis – Summary

![Churn Analysis Summary](./dashboard/dashboardsummary.png)

### Churn Analysis – Prediction

![Churn Prediction Dashboard](./dashboard/dashboardprediction.png)

---

## 📈 Key Results

The Machine Learning model generates customer-level churn predictions that are integrated into Power BI for further analysis.

### Key Dashboard Metrics

* **Total Customers:** 6,418
* **Total Churned Customers:** 1,732
* **Overall Churn Rate:** 26.99%
* **Predicted Churners:** 378

The project goes beyond historical churn reporting by using Machine Learning to identify customers who may be at risk of leaving.

---

## 💡 Business Value

The solution helps answer three important business questions:

### What is happening?

Understand the current level and patterns of customer churn.

### Why is it happening?

Analyze churn based on customer demographics, contracts, services, payment methods, tenure, and other factors.

### Who is likely to churn?

Use Machine Learning predictions to identify customers who may require proactive retention efforts.

This transforms traditional customer reporting into a **predictive customer retention approach**.

---

## 📂 Repository Structure

```text
Customer-Churn-Prediction-Analytics/
│
├── dashboard/
│   ├── dashboardsummary.png
│   └── dashboardprediction.png
│
├── SQL/
│   └── churn_analysis.sql
│
├── Churn Analysis.pbix
├── Prediction_Data.csv
├── Predictions.csv
├── churn prediction.ipynb
├── README.md
└── .gitignore
```

---

## 📁 Project Files

### `churn prediction.ipynb`

Jupyter Notebook containing:

* Data preprocessing
* Data cleaning
* Categorical encoding
* Random Forest model training
* Feature analysis
* Customer churn prediction

### `Churn Analysis.pbix`

Power BI report containing interactive churn analysis and Machine Learning prediction dashboards.

### `Prediction_Data.csv`

Customer dataset used for prediction and analysis.

### `Predictions.csv`

Output generated by the Machine Learning model containing customer-level churn predictions.

### `SQL/`

Contains SQL queries used for data preparation and customer churn analysis.

### `dashboard/`

Contains Power BI dashboard screenshots so the dashboards can be viewed directly from GitHub.

---

## 🔍 Key Insights

The analysis can help identify customer segments with higher churn risk based on factors such as:

* Contract type
* Customer tenure
* Payment method
* Age group
* State
* Internet service
* Customer demographics

The predicted churner analysis allows businesses to prioritize customers who may need retention campaigns or personalized offers.

---

## 🚀 Future Improvements

* Deploy the Machine Learning model as a web application
* Automate the complete data pipeline
* Add real-time churn scoring
* Compare Random Forest with XGBoost and other models
* Add automated customer retention recommendations
* Implement scheduled Power BI data refresh
* Build an API for real-time customer churn prediction

---

## 👨‍💻 Author

**Guna Sekhar**

**B.Tech – Computer Science Engineering**

### Skills Demonstrated

**SQL | Python | Machine Learning | Random Forest | Power BI | Data Analytics | Data Visualization**
