# 📊 Online Retail Sales & Customer Analytics

## 📌 Project Overview

This project analyzes an online retail dataset using **Python and Pandas** to understand sales performance, product performance, customer behaviour, customer retention, country-wise sales, cancellations, and monthly growth.

The main objective of this project is to transform raw transactional data into meaningful business insights that can support data-driven decision-making.

---

## 🎯 Objectives

The project focuses on answering key business questions such as:

- How is the overall business performing?
- Which products generate the most revenue?
- Who are the most valuable customers?
- How frequently do customers make purchases?
- What percentage of customers are repeat customers?
- Which countries generate the most revenue?
- What is the cancellation rate?
- Which months show strong growth or decline?
- What business opportunities can be identified from the data?

---

## 🗂️ Dataset

The project uses an **Online Retail II dataset** containing transactional information from an online retail business.

### Main Columns

| Column | Description |
|---|---|
| `Invoice` | Unique invoice/order number |
| `StockCode` | Product identification code |
| `Description` | Product description |
| `Quantity` | Number of units purchased |
| `InvoiceDate` | Date and time of transaction |
| `Price` | Price per unit |
| `Customer ID` | Unique customer identifier |
| `Country` | Customer's country |

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **Jupyter Notebook**

### Pandas Concepts Used

- Data loading and inspection
- Missing value handling
- Duplicate removal
- Data type conversion
- String manipulation
- Boolean filtering
- GroupBy and aggregation
- Merging and transformation
- Date & time analysis
- Feature engineering
- Customer segmentation
- Statistical calculations
- Business analysis

---

# 🔄 Project Workflow

The project follows the following analytical workflow:

### 1. Data Loading & Understanding

- Loaded the dataset using Pandas
- Inspected rows and columns
- Checked data types
- Examined dataset dimensions
- Generated descriptive statistics

### 2. Data Cleaning

- Handled missing Customer IDs
- Removed missing product descriptions
- Removed duplicate records
- Converted `InvoiceDate` to datetime
- Converted `Customer ID` to integer
- Removed invalid quantities
- Removed invalid prices
- Identified and excluded cancelled invoices from the main sales analysis
- Cleaned product descriptions

### 3. Feature Engineering

Created new analytical features:

- `Total_Sales`
- `Year`
- `Month`
- `Day`
- `Day_Name`
- `Hour`
- `Year_Month`

The main sales metric was calculated as:

**Total Sales = Quantity × Price**

---

# 📊 Analysis Performed

## Overall Sales Performance

Analyzed:

- Total revenue
- Total quantity sold
- Total orders
- Total customers
- Total products
- Average Order Value (AOV)
- Average product price

---

## 📈 Sales Trend Analysis

Analyzed sales across:

- Year
- Month
- Day
- Day of the week
- Hour
- Actual transaction dates

---

## 📦 Product Performance

Identified:

- Top products by revenue
- Top products by quantity sold
- Top products by number of orders
- Lowest-performing products
- Most expensive products

---

## 👥 Customer Analysis

Analyzed customers based on:

- Total spending
- Number of orders
- Average Order Value
- Total quantity purchased

Identified:

- Highest-spending customers
- Most frequent customers
- Customers with the highest AOV
- Customers purchasing the highest quantity

---

## 🧩 Customer Segmentation

Customers were segmented based on the number of orders:

| Segment | Number of Orders |
|---|---:|
| New | 1 |
| Returning | 2–4 |
| Loyal | 5+ |

The segments were compared based on:

- Number of customers
- Revenue
- Average spending
- Average Order Value
- Average number of orders
- Revenue contribution

> **Note:** These customer segment thresholds are defined specifically for this project and are not universal industry standards.

---

## 🔄 Customer Purchase Behaviour

Analyzed relationships between:

- Order frequency
- Total spending
- Average Order Value
- Total quantity purchased

Correlation analysis was also used to understand the relationship between purchase frequency and customer spending.

---

## 🌍 Country-wise Sales Analysis

Compared countries based on:

- Total revenue
- Total quantity
- Number of orders
- Number of customers
- Average Order Value
- Revenue contribution

---

## ❌ Cancellation Analysis

Analyzed:

- Cancelled orders
- Cancelled quantity
- Cancellation rate
- Country-wise cancellations
- Products with the highest cancelled quantity

---

## 🔁 Repeat Customer Analysis

Compared:

- One-time customers
- Repeat customers

Analyzed:

- Repeat customer rate
- Revenue contribution
- Average spending
- Average Order Value
- Average number of orders

---

## 📅 Monthly Growth Analysis

Calculated:

- Monthly revenue
- Month-over-month growth
- Highest revenue month
- Lowest revenue month
- Highest growth month
- Biggest revenue decline

---

# 💡 Key Business Insights

The analysis generated several important business insights:

### 🇬🇧 1. Strong UK Market

The United Kingdom generated approximately **£14.39 million** in revenue and contributed **82.82% of total revenue**, making it the dominant market.

### 🔄 2. Repeat Customers Are Extremely Valuable

Repeat customers generated approximately **£16.81 million** in revenue and contributed **96.78% of customer revenue**.

This highlights the importance of customer retention.

### 📦 3. Top-performing Product

**REGENCY CAKESTAND 3 TIER** was the highest-revenue-generating product, generating approximately **£277,656** in revenue.

### 👑 4. High-value Customer

Customer **18102** was the highest-spending customer, with approximately **£580,987** in total spending across **145 orders**.

### 📈 5. Strongest Growth

**September 2011** recorded the highest month-over-month revenue growth of approximately **47.61%**.

### 📉 6. Significant Revenue Decline

**December 2011** experienced the largest month-over-month revenue decline of approximately **55.27%**.

This suggests that the period should be investigated further to understand the factors behind the decline.

---

# 💼 Business Recommendations

Based on the analysis:

1. Focus on retaining existing customers through loyalty programs and targeted offers.
2. Develop personalized strategies for high-value customers.
3. Continue promoting high-performing products.
4. Investigate reasons behind cancelled orders.
5. Strengthen the UK market while exploring opportunities in other markets.
6. Analyze successful growth periods to identify strategies that can be repeated.
7. Investigate significant periods of revenue decline and identify their underlying causes.

---
