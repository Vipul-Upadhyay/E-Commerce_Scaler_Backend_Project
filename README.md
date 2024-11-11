# E-Commerce Scaler Backend Project

## Overview
This project is an e-commerce backend application built using Java, Spring Boot, and Maven. It provides RESTful APIs for managing products, orders, customers, and other e-commerce functionalities.

## Features
- User authentication and authorization
- Product management (CRUD operations)
- Order management (CRUD operations)
- Customer management (CRUD operations)
- Integration with SQL database

## Technologies Used
- Java
- Spring Boot
- Maven
- SQL

## Getting Started

### Prerequisites
- Java 11 or higher
- Maven 3.6 or higher
- SQL database (e.g., MySQL, PostgreSQL)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/E-Commerce_Scaler_Backend_Project.git
   cd E-Commerce_Scaler_Backend_Project
   ```
## Configuration
1. Configure the database connection in src/main/resources/application.properties:
```sh
spring.datasource.url=jdbc:mysql://localhost:3306/your-database
spring.datasource.username=your-username
spring.datasource.password=your-password
```
2. Build the project:
```sh
mvn clean install
```
3. Run the application:
```sh
mvn spring-boot:run
```
## Usage
The application exposes RESTful APIs for managing e-commerce functionalities. You can use tools like Postman or cURL to interact with the APIs.  
### API Endpoints
- POST /api/auth/signup - Register a new user
- POST /api/auth/login - Authenticate a user
- GET /api/products - Retrieve all products
- POST /api/products - Create a new product
- GET /api/orders - Retrieve all orders
- POST /api/orders - Create a new order
- GET /api/customers - Retrieve all customers
- POST /api/customers - Create a new customer
## License
This project is licensed under the MIT License. See the LICENSE file for details.
