# Online Bookstore SQL Project

## Project Overview
This project analyzes an online bookstore database using SQL.  
The database contains information about books, customers, and orders.  
Various SQL queries are used to retrieve insights and perform data analysis.

## Database Structure

The database contains three main tables:

### 1. Books
- Book_ID (Primary Key)
- Title
- Author
- Genre
- Published_Year
- Price
- Stock

### 2. Customers
- Customer_ID (Primary Key)
- Name
- Email
- Phone
- City
- Country

### 3. Orders
- Order_ID (Primary Key)
- Customer_ID (Foreign Key)
- Book_ID (Foreign Key)
- Order_Date
- Quantity
- Total_Amount

## SQL Concepts Used

- SELECT
- WHERE
- GROUP BY
- ORDER BY
- LIMIT
- JOIN
- Aggregate Functions
- Foreign Keys
- Data Type Modification

## Sample Analysis

Some of the queries performed:

- Find the most expensive book
- Calculate total revenue
- Identify the most frequently ordered book
- Find customers who placed multiple orders
- Calculate remaining stock after orders

## Tools Used

- MySQL Workbench
- SQL
- GitHub

## Author
Supreet Kaur
