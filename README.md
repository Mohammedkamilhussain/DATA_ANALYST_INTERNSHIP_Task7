# DATA_ANALYST_INTERNSHIP_Task7
The entire project was done in Jupyter Notebook, allowing for full integration of database creation, execution of SQL and subsequent visualization in one interactive workflow. Specifically, we wanted to connect Python with a small SQLite database (sales_data.db), extract key sales metrics, and present both a table and bar chart for the results.

**Basic Sales Summary using Python (Jupyter Notebook) and SQLite Database**

This project shows how to connect Python to a small SQLite database within Jupyter Notebook, run SQL queries to summarize sales data from the database and generate a bar chart to visualize the summarized product sales. The complete workflow, from creating the database to generating and saving a visualization, is accomplished interactively in a single notebook.

 What I Did:

-Created the Database in Jupyter.
-Used the built-in sqlite3 module in Python to created sales_data.db.
-Created a sales table with four columns: sale_date, product, quantity and price.
-Inserted sample sales records straight from cells in the notebook.
-Run SQL Queries.

Wrote a basic SQL query to calculate the following:

-Total quantity sold by product
-Total revenue by product (SUM(quantity * price))
-I employed GROUP BY to aggregate the results by product.

Loaded Results with pandas:

-Used pandas.read_sql_query() to load the query results into a DataFrame.
-Displayed the results nicely in the notebook output.
-Visualized Data with matplotlib.
-Created a bar chart which showed Revenue by Product.
-Provided axis labels and a title for clarity and ease of understanding.
-Saved the chart as sales_chart.png.

 Tools & Libraries:

Jupyter Notebook – interactive development
Python 3 – programming language
SQLite – database engine (built-in Python)

pandas – for loading and transforming data

matplotlib – for plotting
