# Project Explanation

## Objective

The objective of this project is to analyze sales data using SQL and generate meaningful business insights.

This project focuses on understanding:

* Customer behavior
* Product performance
* Sales trends over time

---

## Problem Statement

Businesses generate large amounts of sales data, but without proper analysis, it is difficult to understand performance and make decisions.

This project aims to:

* Analyze sales data
* Identify trends and patterns
* Generate insights for better decision-making

---

## Approach

### Step 1: Data Understanding

* Worked with structured tables:

  * fact_sales
  * dim_customers
  * dim_products

---

### Step 2: Data Analysis Using SQL

#### 1. Change Over Time Analysis

* Analyzed yearly and monthly sales trends
* Used:

  * YEAR()
  * MONTH()
  * DATETRUNC()

---

#### 2. Cumulative Analysis

* Calculated running total of sales
* Used window function:

  * SUM() OVER (ORDER BY)

---

#### 3. Performance Analysis

* Compared product performance with:

  * Average sales
  * Previous year sales

* Used:

  * CTE
  * AVG() OVER
  * LAG()

---

#### 4. Part-to-Whole Analysis

* Calculated contribution of each category to total sales

---

#### 5. Data Segmentation

**Customer Segmentation**

* VIP → High spending + long-term customers
* Regular → Medium spending customers
* New → Recent customers

**Product Segmentation**

* Based on cost ranges

* Used:

  * CASE WHEN
  * DATEDIFF()

---

#### 6. Customer Report

Created KPIs such as:

* Total orders
* Total sales
* Recency
* Average order value
* Average monthly spend

---

#### 7. Product Report

Created product insights including:

* Total sales
* Total orders
* Product performance category
* Average revenue

---

## SQL Concepts Used

* Joins
* Aggregations
* CTE (Common Table Expressions)
* Window Functions
* CASE WHEN
* Data segmentation

---

## Outcome

This project demonstrates how SQL can be used to:

* Analyze large datasets
* Extract meaningful insights
* Support business decision-making

---

## Conclusion

Through this project, I developed strong SQL skills and learned how to perform end-to-end data analysis using structured data.
