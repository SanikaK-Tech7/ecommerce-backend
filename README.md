# E-Commerce Backend

A RESTful backend application built with Java Spring Boot and MySQL.

## Technologies Used
- Java 21
- Spring Boot 4.0.7
- MySQL
- Spring Data JPA
- Maven

## Features
- Add products
- View all products
- Delete products

## API Endpoints
| Method | URL | Description |
|--------|-----|-------------|
| GET | /api/products | Get all products |
| POST | /api/products | Add a product |
| DELETE | /api/products/{id} | Delete a product |

## How to Run
1. Clone the project: `git clone https://github.com/SanikaK-Tech7/ecommerce-backend.git`
2. Open it in IntelliJ
3. Create a MySQL database and update the username and password in `src/main/resources/application.properties`
4. Run the main class
5. Test the APIs at `http://localhost:8080/api/products`

## Author
Sanika K | [GitHub](https://github.com/SanikaK-Tech7)
