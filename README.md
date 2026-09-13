# Superstore Sales Analysis & Profitability Prediction

## 📌 Project Overview

This project analyzes over 51,000 sales transactions to understand
sales performance, profitability, customer behavior, and future
sales trends.

The project follows an end-to-end Data Science workflow, from data
cleaning and exploratory data analysis to customer segmentation,
machine learning, and sales forecasting.

## 🎯 Objectives

- Analyze sales and profit performance
- Identify top-performing products and regions
- Analyze the relationship between discount and profit
- Segment customers using RFM analysis
- Predict whether an order will be profitable
- Forecast sales using historical trends
- Provide actionable business recommendations

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 🔍 Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Customer Analysis & RFM
6. Machine Learning
7. Sales Forecasting
8. Business Insights & Recommendations

## 🤖 Machine Learning

Three classification models were evaluated:

| Model | Accuracy |
|---|---:|
| Logistic Regression | 91.87% |
| Decision Tree | 91.93% |
| Random Forest | 91.89% |

The Decision Tree achieved the highest accuracy of **91.93%**.

Feature importance analysis showed that **discount was the dominant
predictive feature** for order profitability in the Decision Tree.

## 📈 Sales Forecasting

Two forecasting approaches were compared:

| Method | MAE |
|---|---:|
| 3-Month Moving Average | 43,265.67 |
| Linear Regression | 39,304.62 |

Linear Regression performed better than the moving-average baseline
at capturing the overall sales trend.

## 💡 Key Business Insights

- Technology generated the highest total sales.
- Central was the strongest region in both total sales and profit.
- Higher discounts were associated with lower profitability.
- High sales did not always guarantee high profit.
- RFM analysis identified different customer segments.
- Historical sales showed an overall upward trend from 2011 to 2014.

## 📊 Business Recommendations

- Prioritize high-performing products while monitoring profitability.
- Maintain strong inventory and investment in high-performing regions.
- Review discount strategies to protect profit margins.
- Evaluate both revenue and profitability when making business decisions.
- Use RFM segments to create targeted customer retention strategies.
- Use sales trends to support inventory planning and sales targets.

## 📁 Project Structure

```text
Superstore-Sales-Analysis/
│
├── SuperStoreOrders.csv
├── Super_store.ipynb
└── README.md
