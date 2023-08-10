# Sprint7-Project

---

## Project Description

Project for Sprint 7 - Exploring and Cleaning Data with Pandas

Sprint 7's project is about Instacart. Instacart is a grocery delivery platform where customers can place a grocery order and have it delivered to them, similar to how Uber Eats and Door Dash work. This particular dataset was publicly released by Instacart in 2017 for a Kaggle competition.

The dataset provided have modified from the original by Practicum. They reduced the size of the dataset so calculations run faster and introduced missing and duplicate values. They were also careful to preserve the distributions of the original data when making the changes.

The necessary datasets that were provided are named: /aisles.csv, /departments.csv, /instacart_orders.csv, /order_products.csv, and /products.csv

The goal of this project is to clean up the data and prepare a report that gives insight into the shopping habits of Instacart customers.
This project also required good visulazations to communicate my findings from the datasets.

---

## DATA DICTIONARY

##### /aisles.csv

- 'aisle_id': ID number that uniquely identifies each grocery aisle category
- 'aisle': name of the aisle

##### /departments.csv

- 'department_id': ID number that uniquely identifies each grocery department category
- 'department': name of the department

##### /instacart_orders.csv: **_each row corresponds to one order on the Instacart app_**

- 'order_id': ID number that uniquely identifies each order
- 'user_id': ID number that uniquely identifies each customer account
- 'order_number': the number of times this customer has placed an order
- 'order_dow': day of the week that the order placed (which day is 0 is uncertain)
- 'order_hour_of_day': hour of the day that the order was placed
- 'days_since_prior_order': number of days since this customer placed their previous order

##### /order_products.csv: **_each row corresponds to one item placed in an order_**

- 'order_id': ID number that uniquely identifies each order
- 'product_id': ID number that uniquely identifies each product
- 'add_to_cart_order': the sequential order in which each item was placed in the cart
- 'reordered': 0 if the customer has never ordered this product before, 1 if they have

##### /products.csv: **_each row corresponds to a unique product that customers can buy_**

- 'product_id': ID number that uniquely identifies each product
- 'product_name': name of the product
- 'aisle_id': ID number that uniquely identifies each grocery aisle category
- 'department_id': ID number that uniquely identifies each grocery department category
