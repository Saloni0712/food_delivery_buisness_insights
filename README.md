# Food Delivery Analytics

## Overview

This repository contains a data analysis project focused on understanding customer behavior, restaurant performance, and revenue trends in a food delivery platform.
The analysis combines order transactions with user membership data and restaurant metadata to answer practical business questions.

---

## Data Sources

The project uses three datasets:

* **food_delivery_data/orders.csv** – Order-level transactional data including order date and total amount
* **food_delivery_data/users.json** – User information such as city and membership type
* **food_delivery_data/restaurants.sql** – Restaurant details including cuisine and ratings

---

## Approach

* Loaded and validated all datasets
* Merged data using `user_id` and `restaurant_id` as keys
* Used a single consolidated dataset for all analysis
* Performed aggregations and comparisons to answer predefined business questions
* Added visualizations to support key findings
* Generated a dynamic summary directly from the analysis results

---

## Key Analysis Areas

* Revenue contribution by city and membership type
* Impact of Gold membership on order volume and value
* Cuisine-level performance and average order values
* Restaurant rating ranges and their revenue contribution
* Seasonal revenue trends (quarterly analysis)

---

## Tools Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* SQLite
* Jupyter Notebook / Google Colab

---

## How to Run

1. Clone the repository
2. Open the notebook in Jupyter Notebook or Google Colab
3. Place all dataset files in the working directory
4. Run the notebook top to bottom

---

## Notes

* All joins are left joins to avoid dropping order data
* The executive summary updates automatically when the notebook is re-run
* Results depend on the input data provided in the repository

---

## Purpose

This project is intended as a portfolio-style analysis and a reference for structured, question-driven exploratory data analysis.

---
