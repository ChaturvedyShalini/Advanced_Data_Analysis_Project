# Dataset Description

## Overview

This project uses a structured sales dataset organized in a data warehouse style (fact and dimension tables).

---

## Tables Used

### fact_sales

Contains transaction-level data:

* order_number
* order_date
* customer_key
* product_key
* sales_amount
* quantity

---

### dim_customers

Contains customer information:

* customer_key
* customer_number
* first_name
* last_name
* birthdate

---

### dim_products

Contains product details:

* product_key
* product_name
* category
* subcategory
* cost

---

## Note

The dataset is not uploaded due to size limitations.

You can use any sample sales dataset to run the queries.
