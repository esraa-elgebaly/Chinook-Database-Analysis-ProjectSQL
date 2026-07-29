# Chinook-Database-Analysis-ProjectSQL
A comprehensive data analysis project exploring the Chinook Database (a digital music store sample database) using SQL, Python

Project Overview
This project explores the relational structure of the Chinook Database to extract actionable business insights regarding music sales, customer revenue distributions, and artist popularity. By combining SQL queries with Python data manipulation and visualization libraries (Matplotlib), this workflow demonstrates how to turn raw relational data into meaningful insights.

About the Chinook Database
The Chinook Database is a standard sample database inspired by the classic Northwind database, representing a digital music store.

Size: Small-to-medium sized dataset consisting of 11 relational tables and ~16,600 rows.

Key Entities:

Customer & Invoice / InvoiceLine (Sales and customer details)

Artist & Album (Music metadata)

Track & Genre (Song details and categorization)

Tools and Technologies
Google Colab: Cloud-based platform used to execute Python code and SQL queries seamlessly.

SQLite: Lightweight database engine used to host and query the Chinook database.

Pandas: For data cleaning, structuring, and manipulation.

Matplotlib: For rendering data visualizations and trends.

Graphviz: For generating the Entity Relationship Diagram (ERD) schema.

Key Findings & Insights
Top-Selling Genres: Rock is the top-selling genre by a wide margin (with a track count of 1,297), followed by Latin.

Revenue by Country: The USA contributes the highest revenue ($523.06), followed by countries like Canada and Brazil.

Top Performing Artists: Artists like Iron Maiden lead the charts in terms of overall catalog/album representation and sales.

Artist vs. Genre Trends: Cross-referencing top artists with genres reveals strong concentrations, such as U2 dominating performance metrics within the Rock category.
