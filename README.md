# Fundamental-SQL-Using-SELECT-Statement
Project from Branch A “So, can you prepare sales transaction data with total revenue >= IDR 100,000? The data format that you will display is: customer_code, product_name, qty, price, and total, and sorted from the largest total revenue,".
If this is the case, it means that I need to query the data from the tr_sales table in the company database.

I can do

multiplication between the qty and price columns to get the total revenue for each customer code expressed in the total column, and
use “ORDER BY total DESC” at the end of the query to sort the data.
