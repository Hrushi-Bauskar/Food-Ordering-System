# Food Ordering System

## Description

The Food Ordering System is a Java-based application that allows users to browse a menu, place orders, and manage their orders efficiently. The system is built using Core Java, JDBC for database connectivity, and SQL for data management.

## Features

- User Registration & Authentication
- Browse Food Menu
- Place and Cancel Orders
- View Order History
- Admin Panel for Managing Menu Items and Orders

## Technologies Used

- **Core Java** for application logic
- **JDBC** for database connectivity
- **SQL** for data storage

## Setup Instructions

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/food-ordering-system.git
   cd food-ordering-system
   ```
2. **Set up the database:**
   - Install MySQL or any preferred relational database.
   - Create a database and import the provided SQL schema.
3. **Configure database connection:**
   - Update `db.properties` or modify JDBC connection details in the code.
4. **Compile and Run the Project:**
   ```sh
   javac -cp .;mysql-connector-java-8.0.26.jar Main.java
   java -cp .;mysql-connector-java-8.0.26.jar Main
   ```

## Usage

- Run the application.
- Register/Login as a user.
- Browse menu and place orders.
- Admins can log in to manage menu items and orders.
