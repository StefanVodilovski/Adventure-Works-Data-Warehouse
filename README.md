# Adventure-Works-Data-Warehouse
Design of a simple Data Warehouse for an E-Commerce site Adventure Works.
----------------------------------------------------------------------------
Design process is below, will be updated as it's being developed 

I'm using Sql server and Azure Data studio for development tools.

If you want to recreate you can download the 2022 database from:
https://github.com/Microsoft/sql-server-samples/releases/tag/adventureworks 

Detailed steps of the development are in the notebook in brief we have:
* Design: Single fact table which measures the quantity and total price of a product sold, per customer, per shipping method on each day.
  -- 
* Development: ETL steps using only SQL (with stored procedures)

