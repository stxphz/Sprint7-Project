# Sprint7-Project

---

## Project Description

Project for Sprint 7 - Exploring and Cleaning Data with Pandas

Sprint 7's project is about Instacart. Instacart is a grocery delivery platform where customers can place a grocery order and have it delivered to them, similar to how Uber Eats and Door Dash work. This particular dataset was publicly released by Instacart in 2017 for a Kaggle competition.

The dataset provided has been modified from the original by Practicum. They reduced the size of the dataset so calculations can run faster. Practicum also introduced missing and duplicate values. They were also careful to preserve the distributions of the original data when making the changes.

The necessary datasets that were provided are named: <code>aisles.csv</code>, <code>departments.csv</code>, <code>instacart_orders.csv</code>, <code>order_products.csv</code>, and <code>products.csv</code>

The goal of this project is to clean up the data and prepare a report that gives insight into the shopping habits of Instacart customers.
This project also required good visulazations to communicate my findings from the datasets.

---

## DATA DICTIONARY

<code>aisles.csv</code>:

- <code>'aisle_id'</code>: ID number that uniquely identifies each grocery aisle category
- <code>'aisle'</code>: name of the aisle

  <br> </br>

<code>departments.csv</code>:

- <code>'department_id'</code>: ID number that uniquely identifies each grocery department category
- <code>'department'</code>: name of the department

<br> </br>

<code>instacart_orders.csv</code>: **each row corresponds to one order on the Instacart app**

- <code>'order_id'</code>: ID number that uniquely identifies each order
- <code>'user_id'</code>: ID number that uniquely identifies each customer account
- <code>'order_number'</code>: the number of times this customer has placed an order
- <code>'order_dow'</code>: day of the week that the order placed (which day is 0 is uncertain)
- <code>'order_hour_of_day'</code>: hour of the day that the order was placed
- <code>'days_since_prior_order'</code>: number of days since this customer placed their previous order

<br> </br>

<code>order_products.csv</code>: **each row corresponds to one item placed in an order**

- <code>'order_id'</code>: ID number that uniquely identifies each order
- <code>'product_id'</code>: ID number that uniquely identifies each product
- <code>'add_to_cart_order'</code>: the sequential order in which each item was placed in the cart
- <code>'reordered'</code>: 0 if the customer has never ordered this product before, 1 if they have

<br> </br>

<code>products.csv</code>: each row corresponds to a unique product that customers can buy

- <code>'product_id'</code>: ID number that uniquely identifies each product
- <code>'product_name'</code>: name of the product
- <code>'aisle_id'</code>: ID number that uniquely identifies each grocery aisle category
- <code>'department_id'</code>: ID number that uniquely identifies each grocery department category
