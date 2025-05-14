## Bookstore Database Project

A simple relational database project for managing and analyzing bookstore data using SQL.

## Files

- 'Books.csv' – Contains book details (title, author, price, stock, etc.)
- 'Customers.csv' – Contains customer information (name, location, email, etc.)
- 'Orders.csv' – Contains purchase records (book, customer, date, quantity)
- 'queries.sql' – SQL queries to analyze the data

## Schema Overview

- Books: 'BookID', 'Title', 'Author', 'Genre', 'Price', 'StockQuantity'
- Customers: 'CustomerID', 'Name', 'Email', 'City', 'Country'
- Orders: 'OrderID', 'CustomerID', 'BookID', 'OrderDate', 'Quantity'

## Sample SQL Queries

- Top-selling books  
- Most active customers  
- Revenue by genre  
- Out-of-stock books  
- Orders by country

## Getting Started

1. Import the CSV files into any SQL-compatible database (MySQL, PostgreSQL, SQLite).
2. Execute `queries.sql` to explore and analyze the data.

## Requirements

- Basic SQL knowledge  
- SQL database
