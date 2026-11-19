Q1. CO 4
S.N. Question BL Marks 10
An e-commerce company wants to develop an Order Management System
using Java JDBC and MySQL to manage customer orders. The database
ecommerce_db contains a table named Orders with the following attributes:
• order_id — INT, Primary Key
• customer_name — VARCHAR(100)
• product_name — VARCHAR(100)
• quantity — INT
• unit_price — DOUBLE
• status — VARCHAR(30)
Write a menu-driven Java JDBC application to perform the following
operations:
a) Establish a connection with the MySQL database and insert at least three
order records using PreparedStatement. Handle duplicate order IDs
appropriately.
b) Accept an order status from the user and display all orders with that status
and a quantity greater than 2. Sort the results by unit price in descending
order.
c) Accept an order ID and an additional quantity. Increase the existing
quantity of the specified order by the given amount. Display an appropriate
message if the order does not exist.
d) Accept an order ID and a new status. Retrieve the order details and update
the status only if the order exists and the new status is valid, such as
Pending, Shipped, or Delivered. Display the updated order details.
e) Display the total order value using SUM (quantity * unit_price). Accept an
order ID and delete the corresponding record only if its status is Cancelled.
Display an appropriate message if the order cannot be deleted.


Q2
A college library wants to develop a Library Management REST API
using Spring Boot to manage its book records. Each book record contains
the following fields:
• id — Integer
• title — String
• author — String
• category — String
• availableCopies — Integer
Develop a Spring Boot REST API to perform the following operations:
a) Create a Book model class with appropriate fields, constructors, getters, and
setters.
b) Implement a REST endpoint to add a new book using @PostMapping and
@RequestBody.
c) Implement endpoints to retrieve all books and retrieve a specific book by
its ID using @GetMapping.
d) Implement an endpoint to update a book's details, including its title,
author, category, and available copies, using @PutMapping.
e) Implement an endpoint to delete a book by its ID using @DeleteMapping.
Return appropriate HTTP responses for successful deletion and when the
book is not found.
