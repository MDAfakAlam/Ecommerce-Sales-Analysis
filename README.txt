# 📊 E-commerce Sales Analysis (Python & Jupyter)

## 📌 Project Overview
This project analyzes real-world e-commerce sales data to uncover trends in sales, profitability, customer behavior, and regional performance.  
The goal is to simulate how a data analyst approaches business problems using Python and data analysis libraries.

---

## 🎯 Business Objective
The analysis aims to:
- Understand sales and profit trends over time
- Identify profitable and loss-making product categories
- Analyze customer contribution to revenue and profit
- Evaluate regional and state-wise performance

---

## 🗂 Dataset
- **Name:** Superstore Sales Dataset  
- **Records:** ~10,000 transactions  
- **Features include:**  
  - Order Date, Ship Date  
  - Category, Sub-Category, Product  
  - Sales, Profit, Discount  
  - Customer, Region, State  

---

## 🧹 Data Cleaning & Preparation
Performed using **Python (Pandas)**:
- Converted date columns to datetime format
- Removed duplicate records
- Created derived features:
  - Order Year
  - Order Month
  - Profit Margin

---

## 🔍 Exploratory Data Analysis
The following analyses were conducted in Jupyter Notebook:

### 📈 Sales & Profit Trends
- Identified seasonality and growth patterns
- Observed inconsistency between sales growth and profit growth

### 🧩 Category & Sub-Category Analysis
- Technology emerged as the most profitable category
- Furniture showed high sales but low profit
- Tables and Bookcases were identified as loss-making sub-categories

### 👤 Customer Analysis
- High-revenue customers were not always profitable
- Discount-driven purchasing behavior impacted margins

### 🌍 Regional Analysis
- West and East regions performed strongly
- States like Texas and Ohio generated high sales but negative profit

---

## 📊 Key Business Insights
- Revenue growth does not guarantee profitability
- Discounts significantly impact profit margins
- Profit-focused strategies outperform revenue-only approaches
- Regional pricing and logistics require optimization

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Project Structure
Ecommerce-Sales-Analysis/
│
├── data/
│ └── superstore_raw.csv
│
├── Ecommerce_Sales_Analysis.ipynb
├── README.md
└── requirements.txt


---

## 🚀 Conclusion
This project demonstrates an end-to-end data analysis workflow using Python and Jupyter Notebook, focusing on business-driven insights rather than just visualizations.


