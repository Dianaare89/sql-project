SQL Data Analysis: Film Rental Database
📌 Project Overview

In this project, I used SQL to analyze a film rental database and answer business-related questions using different query techniques.

The goal was to explore the data, identify patterns, and practice core SQL skills like filtering, grouping, joins, and subqueries.

🎯 Objectives
Explore film and rental data using SQL
Answer business questions using queries
Practice real-world SQL techniques
Extract insights from relational data

🗂️ Dataset
The database includes tables such as:

film (movie details)
category (film categories)
actor (actor information)
customer (customer data)
payment (sales transactions)
address, city, country

🛠️ SQL Skills Used
SELECT statements
DISTINCT
CASE statements
JOINs (INNER JOIN, LEFT JOIN)
GROUP BY
Aggregate functions (COUNT, SUM, AVG)
Subqueries

📊 Key Queries & Insights

🔹 Distinct Values
Retrieved all unique replacement costs
📌 Lowest replacement cost: 9.99
🔹 Categorizing Data (CASE + GROUP BY)
Grouped films into cost ranges (low, medium, high)
📌 Films in "low" range: 514
🔹 JOIN Analysis (Film Categories)
Joined multiple tables to analyze film categories
📌 Longest film: 184 minutes (Sports category)
🔹 Aggregation by Category
Counted how many films exist per category
📌 Most common category: Sports (74 films)
🔹 Actor Analysis
Counted how many films each actor appeared in
📌 Top actor: Susan Davis (54 films)
🔹 Data Integrity Check (LEFT JOIN)
Identified addresses not linked to customers
📌 Unused addresses: 4
🔹 Sales Analysis by City
Calculated total revenue by customer location
📌 Highest revenue city: Cape Coral ($221.55)
🔹 Revenue by Location (Country + City)
Combined fields to analyze revenue geographically
📌 Lowest revenue: United States, Tallahassee ($50.85)
🔹 Advanced Query (Subquery)
Calculated average revenue per customer by staff
📌 Top performer: Staff ID 2 ($56.64 avg/customer)

💡 What I Learned
How to write efficient SQL queries
How to join multiple tables to get meaningful data
How to group and aggregate data for insights
How to use subqueries for more advanced analysis
How to answer business questions using SQL

🚀 Next Steps
Connect SQL queries to Power BI for visualization
Work with larger datasets
Practice window functions and advanced SQL

📎 Author

Diana Arevalo
Aspiring Data Analyst | Business Analytics Student
LinkedIn
