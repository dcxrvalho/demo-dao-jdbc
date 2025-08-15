# Study Project: DAO with JDBC

This project was developed as part of my Java studies to apply the **DAO (Data Access Object)** design pattern in practice, performing database operations using **JDBC (Java Database Connectivity)**.

The focus was to build an organized and decoupled structure that clearly separates business logic from data persistence logic.

## Key Concepts

-   **DAO (Data Access Object) Pattern:** Abstraction and encapsulation of all data access. The application interacts with an interface, remaining unaware of the concrete persistence implementation.
-   **Factory Pattern:** Use of a `DaoFactory` class to create and provide instances of DAO objects, facilitating maintenance.
-   **Database Connection Management:** Centralized handling for obtaining and closing JDBC connections.
-   **Exception Handling:** Implementation of custom exceptions to handle data access errors more robustly.

## Features

The project implements a complete CRUD (Create, Read, Update, Delete) for `Seller` and `Department` entities, demonstrating the following operations:

-   Find seller by ID.
-   Find sellers by department.
-   List all sellers.
-   Insert a new seller.
-   Update an existing seller's data.
-   Delete a seller by ID.

## Tech Stack

-   **Java 11**
-   **JDBC (Java Database Connectivity)**
-   **MySQL Connector/J** (JDBC Driver for MySQL)
