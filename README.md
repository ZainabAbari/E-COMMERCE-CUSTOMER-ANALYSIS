# E-COMMERCE-CUSTOMER-ANALYSIS
This project analyzes customer purchasing behavior, churn patterns, and product performance in an e-commerce business.
---

## Project Overview
The objective is to generate business insights that help stakeholders:
* Understand revenue trends
* Identify valuable customer segments
* Monitor churn and retention
* Evaluate product performance

The project demonstrates a complete data analytics workflow, from **data cleaning in Python** to **interactive dashboard development in Power BI**.
---

## Business Questions

This project aims to answer the following key questions:

* How has revenue changed over time?
* What is the current customer churn and return rate?
* Which customer segments contribute the most revenue?
* Which age groups generate the highest sales?
* How does customer recency influence spending behavior?
* Which product categories drive the most revenue?
* What payment methods are most commonly used?
---

## Data Preparation

The dataset contains **customer transaction data** including:

* Customer demographics
* Product categories
* Purchase quantity and price
* Payment methods
* Returns
* Customer churn status

### Data Cleaning Steps

The following preprocessing steps were performed:
* Inspecting dataset structure
* Checking for missing values
* Standardizing column names
* Converting purchase dates to datetime
* Handling missing return values
* Validating revenue calculations

### Feature Engineering
Additional analytical features were created:
* Customer total revenue
* Customer purchase frequency
* Recency of last purchase
* RFM segmentation scores
* Customer age groups

These features enable deeper customer behavior and segmentation analysis.
---

## 📊 Dashboard Structure

The Power BI dashboard contains three analytical pages.
---

### 1️. Business Overview

<img src="Ecommerce png 1.png" width="900"/>

This page provides a  summary of business performance.
Key metrics include:
* Total Revenue
* Total Customers
* Total Orders
* Average Order Value
* Churn Rate
* Return Rate

Key visuals:
* Revenue trend over time
* Revenue by gender
* Product category performance

---

### 2️. Customer Behavior & Segmentation

<img src="Ecommerce png 2.png" width="900"/>

This page focuses on **customer activity and segmentation analysis**.

Key insights include:

* Customer distribution by RFM score
* Revenue contribution by age group
* Customer churn analysis
* Recency vs monetary value relationship

This helps identify **high-value customers and potential churn risks**.
---

### 3️. Product & Sales Performance

<img src="Ecommerce png 3.png" width="900"/>

This section analyzes product-level sales performance.

Key visuals include:

* Revenue by product category
* Returns by product category
* Payment method distribution
* Quantity vs revenue relationship

These insights support product and operational decision making.
---

## Key Insights

### Revenue Performance

The business generated 681M in revenue from 250K orders across 50K customers.

Revenue remained relatively stable between 2020 and 2022, but declined in **2023**, indicating a potential drop in customer purchasing activity.
---

### Customer Demographics

Customers aged 45–64 generate the highest share of revenue, suggesting this demographic represents the core customer base.
---

### Customer Activity

Customers with recent purchases tend to spend more, while customers with long inactivity periods show significantly lower spending.

This highlights the importance of customer retention strategies.
---

### Churn & Returns

The analysis reveals:
* 20% customer churn rate
* 41% product return rate

The high return rate may indicate issues related to product expectations, logistics, or product quality.
---

### Product Sales

Revenue is evenly distributed across product categories, suggesting a diversified product portfolio.
---

## Business Recommendations
Based on the analysis, the following strategies may improve business performance:

* Implement retention campaigns for inactive customers
* Investigate causes of high return rates
* Target marketing toward high-value age groups
* Encourage repeat purchases through loyalty programs
* Monitor revenue trends to understand recent sales declines
---

## 🔗 Project Files

📘 Python Analysis Notebook
[View Notebook](notebook/Ecommerce-customer-analysis.ipynb) 

📊 Power BI Dashboard
[Download Dashboard](dashboard/Ecommerce dashboard.pbix)
---

## 🚀 Future Improvements
Potential enhancements include:
* Customer Lifetime Value analysis
* Predictive churn modeling
* Product recommendation systems
---

##  Author
Zainab Abari
