

# E-commerce_analysis_project_using_SQL

Analyzed an e-commerce database using SQL to extract insights on sales performance, revenue by category, customer behavior, and regional trends using clean, optimized, production-ready queries.

<img width="826" height="439" alt="Screenshot 2026-01-07 165426 - Copy" src="https://github.com/user-attachments/assets/ded82649-111f-4606-8dce-f1962bcfbaf7" />


# 🧩 Database Schema

The project uses the following relational tables:

customers – customer details and location

orders – order-level information

order_items – item-level sales data

products – product details and pricing

category – product categorization

payments – payment status and dates

inventory – stock and warehouse details

sellers – seller information

shipping – shipping and delivery status

All queries are written strictly using the available schema without assuming extra columns.

# ER-Diagram

![erd ](https://github.com/user-attachments/assets/4ad0c944-7694-4cff-8055-837d94ecb56d)

# 🎯 Key Objectives

Analyze sales and revenue performance

Identify top and least-performing products and categories

Calculate Average Order Value (AOV)

Understand customer purchasing behavior

Perform state-wise and category-wise sales analysis

Use SQL best practices for accuracy and performance

# 🛠️ SQL Concepts Used

INNER JOINs across multiple tables

Aggregate functions (SUM, COUNT, AVG)

GROUP BY and HAVING clauses

Subqueries and correlated subqueries

Common Table Expressions (CTEs)

Window functions (RANK, LAG)

Data ranking and filtering logic

# 📈 Sample Analyses Performed

Top 10 products by total sales value

Category-wise revenue and percentage contribution

Average Order Value (AOV) for customers with more than 5 orders

Customers who never placed an order

Monthly sales trends

Least-selling product category by state

# ✅ Best Practices Followed

Revenue calculated at order-item level

Use of DISTINCT to avoid duplication errors

Grouping by primary keys for data integrity

Window functions preferred over nested subqueries where applicable

Queries written for MySQL 8+ compatibility

# 💼 Use Cases

Data Analyst / SQL Developer interviews

Backend developer SQL assessments

Business Intelligence reporting

Learning advanced SQL analytics on relational data

🚀 How to Use

Create the database tables using the provided schema

Insert sample or real data

Execute the SQL queries in MySQL 8+

Modify queries to explore additional insights

# 🏁 Conclusion

This project demonstrates strong proficiency in SQL-based data analysis, focusing on correctness, performance, and real-world business logic. The queries and approaches used align with industry standards and are directly applicable to professional data analytics and backend engineering roles.
