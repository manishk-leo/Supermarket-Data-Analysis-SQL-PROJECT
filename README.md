# Supermarket-Data-Analysis-SQL-PROJECT

In this project, I used relational database to import the data and extract the necessary information to provide analytical support to the business in making business decisions.
The data is provided with orders placed at various locations in India, people who have returned the items, and customers.

The data set provided has the following tables:
1. TABLE- orders
Order_ID (VARCHAR) - Primary Key for each order placed
Order_Date (VARCHAR) - when was the order placed
Ship_Date (VARCHAR) - when was the order shipped
Customer_ID (VARCHAR) -ID of the customer who placed the order
Segment (VARCHAR) - to which segment does the product sold belongs to
State (VARCHAR) - State where the order was placed
City (VARCHAR) - City where the order was placed
Product_ID (VARCHAR) - ID of the product sold
Category (VARCHAR) - Category of the product Sold
SubCategory (VARCHAR) - Sub category of the product Sold
Product_Name (VARCHAR) - Name of the product sold
Sales (DOUBLE) -Sale price of the order
Quantity (DOUBLE) - Quantity of product for which order was placed
Discount (DOUBLE) - % Discount offered on the MRP
Profit (DOUBLE) - Total Profit made on the order
2. TABLE- customers
Customer_ID (VARCHAR) - ID of the customer, primary key of the table
Customer_Name_ (VARCHAR) - Name of the Customer
3. TABLE- returns
Order_ID (VARCHAR) - Primary key of the order returned
Returned (VARCHAR) - If the order was returned or no
