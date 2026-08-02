# sql-employee-sales-analysis
SQL project analyzing employee and sales data — joins, subqueries, window functions, and visualization

# Employee & Sales Performance Analysis (SQL)

A SQL-based project analyzing employee and sales data through a custom-designed 
relational database, covering joins, subqueries, window functions, and 
data visualization.

## Repository Structure
- `sql_analysis.ipynb` — main notebook (schema design, queries, visualizations)
- `company_combined.csv` — combined view of employees, departments, and sales data (joined for easy reference)
- `README.md` — this file

## How to Run
1. Clone this repo
2. Install dependencies: `pip install pandas matplotlib seaborn`
3. Open `sql_analysis.ipynb` and run cells in order (creates DB, inserts data, 
   runs queries)

## Key Findings
- Identified employees earning above their department's average salary using 
  correlated subqueries
- Ranked employees by salary within each department using window functions
- Determined departments exceeding sales performance thresholds

## SQL Concepts Demonstrated
Joins (INNER, LEFT, Self), Subqueries (correlated), Window Functions (RANK, 
PARTITION BY), CTEs, Aggregations (GROUP BY, HAVING), Constraints 
(PRIMARY KEY, FOREIGN KEY, CHECK)

## Tech Stack
Python, SQLite, pandas, matplotlib, seaborn
