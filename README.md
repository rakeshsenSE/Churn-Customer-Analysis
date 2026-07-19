# Telecom Customer Churn - Exploratory Data Analysis (EDA)

This repository contains a comprehensive Exploratory Data Analysis (EDA) on a Telecom Customer Churn dataset. The primary objective is to identify key factors that drive customer turnover (churn) and provide actionable insights to improve customer retention.

## 📝 Executive Summary
This project analyzes telecom customer data to identify the core drivers behind customer turnover. By leveraging Python's data science ecosystem, the analysis reveals that high churn rates are heavily correlated with non-automated payment methods (Electronic Checks) and short-term (Month-to-Month) contract agreements. These findings offer actionable business intelligence to optimize customer retention strategies and target high-risk customer segments effectively.

## 🎯 Project Objective
* **Understand Churn Drivers:** Analyze customer demographics, account information, and services to identify why customers leave.
* **Data Cleaning & Preprocessing:** Handle missing data, correct data types, and transform variables for better analysis.
* **Data Visualization:** Create meaningful charts (Pie charts, Countplots, Boxplots) to uncover hidden patterns and trends.

## 🛠️ Technologies & Libraries Used
* **Python** (Core Language)
* **Pandas:** For data manipulation, cleaning, and structural analysis.
* **Matplotlib:** For basic plotting and customized chart styling.
* **Seaborn:** For advanced statistical data visualization.

## 📊 Key Insights & Findings
* **High-Risk Payment Method:** Customers paying via **Electronic Check** show a disproportionately high churn rate (1,071 users), almost matching the number of retained customers in that category. Other automated methods show significantly higher retention.
* **Contract Type Impact:** Customers with a **Month-to-Month contract** are highly volatile and significantly more likely to churn compared to those on 1-year or 2-year commitments.
* **Tenure Correlation:** The distribution in the boxplot reveals that **newer customers (lower tenure)** have a substantially higher risk of leaving the service.
* **Overall Churn Rate:** The dataset consists of **26.54% churned customers** versus **73.46% retained customers**, highlighting a clear area of improvement for customer engagement strategies.

## 📁 Repository Structure
* `customer.ipynb`: The main Jupyter Notebook containing data loading, preprocessing, cleaning, and visualizations.
* `requirements.txt`: List of dependencies required to run the project.
* `README.md`: Project documentation.

---
*Developed as part of my continuous learning journey in AI-powered Full Stack Development and Data Science.*
