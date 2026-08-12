# Customer Churn Prediction & Analytics

An end-to-end Customer Churn Prediction project using SQL, Python, Machine Learning, and Power BI to identify customers at risk of churn and generate actionable business insights.

## 📌 Project Overview

Customer churn is a major business problem because losing existing customers can directly impact revenue and growth.

This project analyzes customer behavior, service usage, contract information, and revenue-related attributes to identify customers who are likely to churn.

The project combines data engineering, exploratory analysis, machine learning, and business intelligence into one complete analytics workflow.

## 🎯 Business Objectives

- Identify customers at high risk of churn
- Understand the major factors associated with churn
- Analyze churn across customer segments
- Estimate revenue associated with different customer statuses
- Provide actionable insights through an interactive Power BI dashboard

## 🔄 Project Workflow

SQL Server → Data Cleaning → Python EDA → Machine Learning → Churn Prediction → Power BI Dashboard

## 🛠️ Technologies Used

- **SQL Server** – Data extraction, cleaning, transformation and analysis
- **Python** – Data preprocessing and exploratory analysis
- **Pandas** – Data manipulation
- **Scikit-learn** – Machine learning
- **Random Forest** – Churn prediction model
- **Jupyter Notebook** – Model development and analysis
- **Power BI** – Interactive dashboard and business insights

## 🗄️ SQL Analysis

SQL was used to:

- Inspect customer data
- Check missing values
- Clean and transform customer attributes
- Create the production churn table
- Create analytical views
- Analyze customer demographics
- Analyze contracts and customer status
- Analyze revenue
- Analyze state and internet type

## 🤖 Machine Learning

A **Random Forest Classifier** was used to predict customer churn.

The workflow includes:

1. Data loading
2. Data preprocessing
3. Categorical variable encoding
4. Feature preparation
5. Model training
6. Feature importance analysis
7. Churn prediction
8. Exporting prediction results

## 📊 Power BI Dashboard

The Power BI dashboard provides interactive analysis of:

- Total customers
- Predicted churners
- Churn distribution
- Customer demographics
- Contract type
- Tenure
- Payment method
- Internet service
- Revenue
- Other customer segments

Users can interact with filters and visualizations to identify high-risk customer segments.

## 📁 Repository Structure

```text
Customer-Churn-Prediction-Analytics/
│
├── SQL/
│   └── customer_churn_analysis.sql
│
├── churn prediction.ipynb
├── Prediction_Data.csv
├── Predictions.csv
├── Churn Analysis.pbix
└── README.md
