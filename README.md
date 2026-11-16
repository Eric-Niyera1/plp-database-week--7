
# Database Normalization Assignment

## Question 1: First Normal Form (1NF)
The ProductDetail table was normalized by separating multiple products into individual rows.

## Question 2: Second Normal Form (2NF)
The OrderDetails table was divided into two tables:
- Orders
- OrderItems

## Primary Keys
- Orders: OrderID
- OrderItems: OrderID and Product

## Foreign Key
OrderItems.OrderID references Orders.OrderID.

## Conclusion
Database normalization reduces data duplication,
improves consistency, and organizes information
into related tables.

## Tools Used
- Visual Studio Code
- MySQL
- SQL
