# Task 3 - SQL Querying Fundamentals

**Dataset:** train.csv (Superstore)

### Queries Performed
1. `SELECT * FROM orders LIMIT 10;`
2. `SELECT * FROM orders WHERE region = 'West';`
3. `SELECT customer_name, sales FROM orders ORDER BY sales DESC LIMIT 5;`
4. `SELECT region, SUM(sales) as TotalSales FROM orders GROUP BY region;`

**Tool Used:**  
- Jupyter Notebook (Python + SQLite)
# internship-tasks03
Skillytix Internship Tasks
