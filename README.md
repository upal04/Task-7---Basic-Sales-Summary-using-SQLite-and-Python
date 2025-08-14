# Task 7 — Basic Sales Summary from a Tiny SQLite Database

## Objective
Use SQL inside Python to retrieve total quantity sold and total revenue from a small SQLite database, and display the results with print statements and a basic matplotlib bar chart.

## Tools
- Python (`sqlite3`, `pandas`, `matplotlib`)
- SQLite (built into Python — no setup required)
- Jupyter Notebook or `.py` file

## Dataset
A small SQLite database file (`sales_data.db`) containing one table `sales` with the following columns:
- `product` (TEXT)
- `quantity` (INTEGER)
- `price` (REAL)

## Steps
1. Connect to the database using `sqlite3.connect("sales_data.db")`.
2. Run an SQL query to group sales by product and calculate:
   - Total quantity sold (`SUM(quantity)`)
   - Total revenue (`SUM(quantity * price)`)
3. Load the query results into a Pandas DataFrame.
4. Print the DataFrame.
5. Plot a bar chart of revenue by product.
6. Save the chart as `sales_chart.png` and display it.
<img width="640" height="480" alt="sales_chart" src="https://github.com/user-attachments/assets/5c0592c9-e494-4140-8984-fbe8d41ba95e" />


## Sample Output

<img width="2879" height="1799" alt="image_2025-08-14_141402182" src="https://github.com/user-attachments/assets/5cbb1687-796c-41d4-9a64-5e95fedd6e95" />
