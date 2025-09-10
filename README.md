## 📌 Objective
The goal of this task was to get a basic sales summary from a tiny SQLite database using Python.

## 🛠 Tools Used
- Python
- sqlite3
- pandas
- matplotlib

## 📂 Files Included
- `task6.py` / `task6.ipynb` → Python code for the task
- `sales_data.db` → SQLite database with sample sales data
- `sales_chart.png` → Bar chart showing revenue by product
- `README.md` → Documentation of the task

## 🚀 Steps I Followed
1. Connected Python to SQLite database (`sales_data.db`) using `sqlite3`.
2. Created a `sales_data` table with fields: id, date, product, quantity, price.
3. Inserted sample records into the table.
4. Ran SQL queries to:
   - Get sales where quantity > 2
   - Summarize total quantity & revenue per product
5. Loaded query results into pandas DataFrames.
6. Displayed results using `print()`.
7. Created a bar chart (`Revenue by Product`) using matplotlib and saved it as `sales_chart.png`.

## 📊 Output
- A printed summary of sales data in the terminal.
- A bar chart showing **Total Revenue by Product**.

## ✅ Learning Outcomes
- Connecting Python with SQLite
- Running SQL queries inside Python
- Using pandas for data analysis
- Creating visualizations with matplotlib
