# Adventure-Works-Data-Warehouse
Design of a simple Data Warehouse for an E-Commerce site Adventure Works

If you want to recreate you can download the database from:
https://github.com/Microsoft/sql-server-samples/releases/tag/adventureworks 
* I worked with the 2022 version

Inital design: 
* Single fact table which measures the quantity and total price of a product sold, per customer, per shipping method on each day.

The inital steps are to design the ETL proccess:
* the simplest step: using only SQL (with stored procedures)
