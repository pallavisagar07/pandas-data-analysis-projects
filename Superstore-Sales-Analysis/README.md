# Superstore Sales Analysis

An end-to-end data analysis project using **Python and Pandas** to clean, transform, and analyze Superstore sales data and extract meaningful business insights.

## 📌 Project Overview

The goal of this project is to work with a real-world sales dataset and follow a typical data analysis workflow—from understanding and cleaning raw data to transforming it and identifying useful patterns.

The project focuses on understanding **sales performance, customer segments, product categories, regional performance, and shipping patterns**.

## 🎯 Objectives

* Understand the structure and quality of the dataset
* Clean and prepare the raw data for analysis
* Handle missing and duplicate data
* Transform date, text, and numerical columns


## 🗂️ Dataset

**Dataset:** Superstore Sales Dataset

The dataset contains information about customer orders, products, sales, shipping, and geographic regions.

### Main Features

| Category             | Columns                                          |
| -------------------- | ------------------------------------------------ |
| Order Information    | Order ID, Order Date, Ship Date, Ship Mode       |
| Customer Information | Customer ID, Customer Name, Segment              |
| Location             | Country, City, State, Postal Code, Region        |
| Product Information  | Product ID, Category, Sub-Category, Product Name |
| Sales                | Sales                                            |

The dataset contains **9,800 records** and **18 original columns**.

## 🧹 Data Cleaning

The raw dataset was prepared before performing analysis.

The cleaning process included:

* Inspecting the dataset structure and data types
* Identifying missing values
* Investigating missing postal codes
* Checking and removing duplicate records
* Converting date columns into the appropriate datetime format
* Cleaning and standardizing text values
* Checking numerical columns and data types
* Performing final data-quality checks

### Missing Values

The dataset contains **11 missing Postal Code values**.

These values were not replaced with an arbitrary value because postal codes are location identifiers rather than continuous numerical measurements. Since they could not be reliably inferred from the available data, they were retained as missing values.

## 🔄 Data Transformation

Additional features were created to make the dataset more useful for analysis.

These include:

* **Shipping Duration** — number of days between order and shipment
* **Order Year** — year extracted from the order date
* **Sales Category** — categorization of sales based on the median sales value
* **Order Month** — month extracted from the order date


## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **Jupyter Notebook**

## 📁 Project Structure

```text
Superstore-Sales-Analysis/
│
├── Superstore_Sales_Analysis.ipynb
├── superstore_cleaned.csv
└── README.md
```

## 📈 Key Insights

*This section will be updated after completing the exploratory data analysis and visualization.*

## 🚀 Future Improvements

* Add more detailed exploratory analysis
* Create additional visualizations
* Build an interactive dashboard using Power BI
* Perform deeper customer and product segmentation
* Develop more business-focused recommendations

## 👩‍💻 About the Project

This project was created as part of my hands-on learning in **data analysis with Python and Pandas**.

The focus was not only on learning individual Pandas functions, but on applying them to a complete dataset and following a practical data-analysis workflow.
