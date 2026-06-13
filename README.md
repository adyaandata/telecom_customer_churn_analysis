# 📊 Telecom Customer Churn Analysis

## Overview

Customer churn is a major challenge for telecom companies because losing existing customers directly impacts revenue and growth. In this project, I performed Exploratory Data Analysis (EDA) on a telecom customer dataset to understand the factors that influence customer churn and identify patterns that can help improve customer retention.

The analysis focuses on customer demographics, services used, contract types, payment methods, and other factors that may contribute to customers leaving the company.

---

## 🎯 Objectives

- Understand customer churn behavior.
- Identify the characteristics of customers who are more likely to leave.
- Explore relationships between customer services and churn.
- Generate business insights that can help reduce churn.

---

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset

The dataset contains information about telecom customers, including:

- Customer demographics
- Account information
- Services subscribed
- Contract types
- Payment methods
- Monthly charges
- Total charges
- Customer churn status

---

## 🧹 Data Cleaning

The following preprocessing steps were performed before analysis:

- Checked for missing values
- Checked for duplicate records
- Converted data types where required
- Handled blank values in the `TotalCharges` column
- Improved column formatting for easier analysis

---

## 📈 Exploratory Data Analysis

### Customer Churn Distribution

- Analyzed the overall proportion of customers who stayed versus those who left.
- Found that approximately **27% of customers churned**, while **73% remained with the company**.

### Gender vs Churn

- Compared churn rates across male and female customers.
- Observed that gender has little impact on customer churn.

### Senior Citizen vs Churn

- Analyzed churn behavior among senior and non-senior customers.
- Senior citizens showed a higher tendency to leave the service.

### Tenure Analysis

- Examined the relationship between customer tenure and churn.
- Customers with shorter tenure were more likely to churn.
- Long-term customers showed stronger loyalty.

### Contract Type Analysis

- Compared churn rates across different contract types.
- Month-to-Month customers had the highest churn rate.
- One-Year and Two-Year contracts showed better customer retention.

### Service-Based Analysis

The following services were analyzed:

- Phone Service
- Multiple Lines
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies

Key observations:

- Customers without Online Security were more likely to churn.
- Customers without Tech Support showed higher churn rates.
- Fiber Optic users experienced relatively higher churn compared to other internet service types.

### Payment Method Analysis

- Compared churn rates across different payment methods.
- Customers using Electronic Check showed the highest churn levels.

---

## 🔍 Key Insights

- Month-to-Month contract customers are more likely to leave.
- Customers with low tenure have a higher probability of churning.
- Senior citizens exhibit higher churn rates.
- Online Security and Tech Support services contribute positively to customer retention.
- Electronic Check users show increased churn behavior.
- Fiber Optic customers experience relatively higher churn levels.

---

## 💡 Recommendations

Based on the findings, the following actions may help reduce customer churn:

- Encourage customers to switch to long-term contracts.
- Improve onboarding and engagement during the early stages of customer tenure.
- Promote value-added services such as Online Security and Tech Support.
- Investigate factors contributing to churn among Fiber Optic customers.
- Enhance payment experience and encourage alternative payment methods.

---

## 📚 Learning Outcomes

Through this project, I gained hands-on experience in:

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization using Matplotlib and Seaborn
- Customer Churn Analysis
- Extracting Business Insights from Data
- Working with Real-World Datasets

---

## Conclusion

This project explores customer churn patterns in a telecom dataset using Python-based Exploratory Data Analysis. The findings highlight how factors such as contract type, tenure, payment methods, and support-related services influence customer retention. These insights can help businesses better understand customer behavior and develop strategies to reduce churn.
