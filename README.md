Aggregation
Approach:

Extract year and month from order_date using EXTRACT(YEAR FROM order_date) and EXTRACT(MONTH FROM order_date).

Aggregate data using SUM(total) for monthly revenue.

Count unique orders with COUNT(DISTINCT order_id) for order volume.

Group results by year and month using GROUP BY.

Sort the results chronologically using ORDER BY.

Optionally, limit the query to specific time periods using WHERE.

Deliverables:

SQL script implementing the aggregation

Results table showing Year | Month | Revenue | Order Volume
