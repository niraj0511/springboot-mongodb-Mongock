
# Expense Tracker Application

## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Running the Application](#running-the-application)
- [API Endpoints](#api-endpoints)
- [Swagger Documentation](#swagger-documentation)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Expense Tracker Application is a Java-based web application developed using Spring Boot 3, MongoDB for data storage, Mongock for database migration, and Swagger for API documentation. It allows users to manage and track their expenses with CRUD (Create, Read, Update, Delete) operations.

## Technologies Used

- Java 17
- Spring Boot 3
- MongoDB
- Mongock
- Swagger

## Setup

1. **Clone the repository:**

    ```bash
    [git clone https://github.com/your-username/expense-tracker.git](https://github.com/niraj0511/springboot-mongodb-Mongock.git)
    cd springboot-mongodb-Mongock
    ```

2. **Build the application:**

    ```bash
    ./mvnw clean package
    ```

3. **Set up MongoDB:**

    Ensure MongoDB is installed and running locally, or update the application's `application.properties` to point to your MongoDB instance.

4. **Configure application properties:**

    Update `src/main/resources/application.properties` with the appropriate MongoDB and other configuration settings.

## Running the Application

1. **Run the JAR file:**

    ```bash
    java -jar target/expense-tracker-<version>.jar
    ```

   Replace `<version>` with the appropriate version number.

2. **Access the application:**

   Navigate to `http://localhost:8080` in your web browser.

## API Endpoints

The API supports the following CRUD operations:

- **GET /api/expenses**: Retrieve all expenses.
- **GET /api/expenses/{id}**: Retrieve a specific expense by ID.
- **POST /api/expenses**: Create a new expense.
- **PUT /api/expenses**: Update an existing expense.
- **DELETE /api/expenses/{id}**: Delete an expense by ID.

## Swagger Documentation

The API documentation is available using Swagger UI. Access it by navigating to `http://localhost:8080/swagger-ui.html` after starting the application.


---

Feel free to customize this README file to fit the specifics of your project. Add or modify sections based on your application's unique features and requirements.
