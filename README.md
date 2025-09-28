# 📚 Online Bookstore Database Project  

## 1. Project Title / Headline  
🗄️ **Online Bookstore Database with SQL Queries**  
A relational database project for managing an online bookstore, including books, customers, and orders. The project also contains solved SQL queries for beginner to advanced analysis.  

---

## 2. Short Description / Purpose  
The Online Bookstore Database project demonstrates database creation, data import, and query execution using SQL. It models a typical e-commerce bookstore with entities such as **Books**, **Customers**, and **Orders**.  
The project is designed to:  
- Practice SQL schema design  
- Work with relational data (Joins, Aggregations, Grouping)  
- Answer real-world business queries like revenue, customer activity, and stock management  

---

## 3. Tech Stack  
The database was built and queried using:  
• 🐘 **PostgreSQL** – RDBMS used for database creation and queries  
• 💻 **SQL** – DDL (Data Definition Language) & DML (Data Manipulation Language)  
• 📂 **CSV Import** – Data imported into tables from `.csv` files  
• 📝 **SQL Script** – All code and solved queries stored in `Solved Queries.sql`  

---

## 4. Data Model / Tables  
The project includes **3 core tables**:  

- **Books**  
  - `Book_ID`, `Title`, `Author`, `Genre`, `Published_Year`, `Price`, `Stock`  
- **Customers**  
  - `Customer_ID`, `Name`, `Email`, `Phone`, `City`, `Country`  
- **Orders**  
  - `Order_ID`, `Customer_ID`, `Book_ID`, `Order_Date`, `Quantity`, `Total_Amount`  

Relationships:  
- Each **Order** is linked to a **Customer** and a **Book** (via foreign keys).  
- Enables cross-analysis of customer behavior, sales, and inventory.  

---

## 5. Features / Highlights  

**• Business Problem**  
An online bookstore requires a structured way to manage inventory, track sales, and analyze customer orders.  

**• Goal of the Project**  
To design a normalized relational database and provide SQL queries that:  
- Manage and analyze book inventory  
- Track customer orders and spending  
- Calculate total revenue and stock availability  
- Answer both simple and advanced business queries  

**• Example Queries Included**  
- Retrieve all books by genre or published year  
- Find the most expensive/cheapest books  
- Show orders in a given month  
- Calculate total revenue and stock remaining  
- Identify top customers and most sold books  
- Aggregate sales by genre, author, and location  

**• Business Impact & Insights**  
- 📊 Helps bookstore managers identify **best-selling genres & authors**  
- 💰 Tracks **revenue growth and high-value customers**  
- 📦 Ensures better **stock and inventory management**  
- 🌍 Provides insights into **regional demand** (e.g., top countries/cities)  

---
