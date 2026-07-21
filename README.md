# Customer Behavior Analysis

## Project Overview

This project demonstrates an end-to-end Data Analytics workflow using **Python**, **MySQL**, and **Power BI**. The objective is to analyze customer shopping behavior and generate business insights that can help improve sales, customer satisfaction, and customer retention.

The project includes:
- Data cleaning and preprocessing using Python
- Business analysis using SQL
- Interactive dashboards using Power BI
- Business recommendations based on analytical findings

---

## Problem Statement

A retail company wants to understand customer shopping behavior to improve business performance. The analysis focuses on how customer demographics, purchase history, discounts, reviews, payment methods, shipping types, and seasons influence purchasing decisions.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- MySQL
- SQLAlchemy
- PyMySQL
- Power BI

---

## Dataset Information

- Total Records: **3,900**
- Customer Attributes:
  - Customer ID
  - Age
  - Gender
  - Item Purchased
  - Category
  - Purchase Amount
  - Location
  - Size
  - Color
  - Season
  - Review Rating
  - Subscription Status
  - Shipping Type
  - Discount Applied
  - Promo Code Used
  - Previous Purchases
  - Payment Method
  - Frequency of Purchases

---

# Python Data Cleaning

The following preprocessing steps were performed:

- Loaded and explored the dataset
- Checked dataset structure using `info()` and `describe()`
- Identified missing values
- Filled missing Review Ratings using category-wise median
- Standardized column names
- Created Age Group feature
- Converted Purchase Frequency into numerical days
- Removed duplicate column (Promo Code Used)
- Uploaded cleaned dataset to MySQL

---

# SQL Business Analysis

The following business questions were answered using SQL:

1. Revenue by Gender
2. Repeat Buyers by Subscription Status
3. Top 3 Best-Selling Products in Each Category
4. Customer Segment Analysis
5. Top 5 Products with Highest Discount Rate
6. Average Spending and Total Revenue by Subscription Status
7. Average Spending by Shipping Type
8. Top 5 Products by Average Review Rating
9. Customers Who Used Discounts and Spent Above Average
10. Revenue by Age Group

---

# Power BI Dashboard

The dashboard contains two interactive pages.

## Dashboard 1

- Total Customers KPI
- Average Purchase Amount
- Average Review Rating
- Revenue by Category
- Customers by Category
- Revenue by Age Group
- Customers by Age Group

## Dashboard 2

- Revenue by Payment Method
- Revenue by Shipping Type
- Customer Segments
- Average Review Rating by Category
- Revenue by Season
- Discount Analysis

Interactive slicers include:

- Gender
- Category
- Shipping Type
- Subscription Status

---

# Key Business Insights

- Middle-aged customers generated the highest revenue.
- Clothing products performed better than other categories.
- Loyal customers represented the largest customer segment.
- Some products had significantly higher discount usage.
- Shipping method had a small impact on average spending.
- Highly rated products can be promoted to increase customer engagement.

---

# Business Recommendations

- Focus marketing campaigns on middle-aged customers.
- Continue promoting high-performing clothing products.
- Reward loyal customers through loyalty programs.
- Highlight highly-rated products on the homepage.
- Plan seasonal promotions before demand peaks.
- Monitor customer behavior regularly using dashboards.

---

# Project Workflow

```
Dataset
   │
   ▼
Python (Data Cleaning & Feature Engineering)
   │
   ▼
MySQL (Business Analysis)
   │
   ▼
Power BI Dashboard
   │
   ▼
Business Insights & Recommendations
```

---

# Repository Structure

```
Customer-Behavior-Analysis/
│
├── Dataset/
│   └── customer_shopping_behavior.xlsx
│
├── Python/
│   └── Data_Cleaning.ipynb
│
├── SQL/
│   └── Business_Queries.sql
│
├── PowerBI/
│   └── Customer_Behavior_Dashboard.pbix
│
├── Report/
│   └── Customer Behavior Analysis Full Report.pdf
│
├── Images/
│   ├── Dashboard1.png
│   ├── Dashboard2.png
│   └── SQL Results
│
└── README.md
```

---

# Learning Outcomes

Through this project, I practiced:

- Data Cleaning
- Feature Engineering
- SQL Query Writing
- Business Problem Solving
- Data Visualization
- Dashboard Development
- Business Reporting

---

# Author

**Malik**

Aspiring Data Analyst

Skills:
- Python
- SQL
- MySQL
- Power BI
- Excel
- Data Cleaning
- Data Visualization

---

## Project Report

The complete project report is available in this repository.

```
