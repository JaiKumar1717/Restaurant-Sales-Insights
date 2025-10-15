# Pizza Sales Analysis

This repository contains a pizza sales analysis project, including the raw data, SQL queries for analysis, and a Power BI dashboard for visualization.

---

## Files

* **Raw Data.csv**: The raw dataset containing detailed information about pizza orders.
* **SQLQuery1.sql**: A SQL script with queries to analyze the pizza sales data.
* **Power BI Dashboard.pbix**: An interactive Power BI dashboard to visualize the pizza sales data and insights.

---

## Data Description

The Raw Data.csv file contains the following columns:

* pizza_id: A unique identifier for each pizza.
* order_id: The identifier for each order.
* pizza_name_id: The ID of the pizza name.
* quantity: The number of pizzas ordered.
* order_date: The date the order was placed.
* order_time: The time the order was placed.
* unit_price: The price of a single pizza.
* total_price: The total price of the order line.
* pizza_size: The size of the pizza (e.g., S, M, L).
* pizza_category: The category of the pizza (e.g., Classic, Veggie, Supreme, Chicken).
* pizza_ingredients: The ingredients of the pizza.
* pizza_name: The name of the pizza.

---

## SQL Analysis

The SQLQuery1.sql script contains queries to derive the following insights from the data:

* Total Revenue
* Average Order Value
* Total Pizzas Sold
* Total Orders
* Average Pizzas per Order
* Sales by Day of the Week and Month
* Sales Distribution by Pizza Category and Size
* Top and Bottom 5 Best-Selling Pizzas by Revenue, Quantity, and Total Orders

---

## Power BI Dashboard

The Power BI Dashboard.pbix file provides an interactive and visual representation of the pizza sales data. The dashboard likely includes visualizations of the key metrics and insights from the SQL analysis, allowing for a deeper exploration of the data.

---

## How to Use

1.  *SQL Database*: Import the Raw Data.csv file into a SQL database.
2.  *Run Queries*: Execute the queries in SQLQuery1.sql against the imported data to perform the analysis.
3.  *Power BI*: Open the Power BI Dashboard.pbix file in Power BI Desktop. You may need to update the data source to connect to your SQL database.
