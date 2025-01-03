# EMS-Backend-SpringBoot
# EMS Backend Spring Boot Project

## Overview

This is a simple backend project using Spring Boot. The project provides RESTful APIs for managing departments in an organization.

## Prerequisites

- Java 8 or higher
- Maven
- Postman (for testing the APIs)

## Getting Started

1. **Clone the repository**:
    ```bash
    git clone https://github.com/mithun-R-777/EMS-Backend-SpringBoot.git
    cd EMS-Backend-SpringBoot
    ```

2. **Build the project**:
    ```bash
    mvn clean install
    ```

3. **Run the application**:
    ```bash
    mvn spring-boot:run
    ```

## API Endpoints

You can use Postman to test the following endpoints:

1. **Save Department**
    - **URL**: `POST /departments`
    - **Description**: Save a new department.
    - **Request Body**:
        ```json
        {
            "name": "Department Name",
            "description": "Department Description"
        }
        ```

2. **Get Department by ID**
    - **URL**: `GET /departments/{id}`
    - **Description**: Retrieve a department by its ID.

3. **Delete Department by ID**
    - **URL**: `DELETE /departments/{id}`
    - **Description**: Delete a department by its ID.

4. **Update Department by ID**
    - **URL**: `PUT /departments/{id}`
    - **Description**: Update a department by its ID.
    - **Request Body**:
        ```json
        {
            "name": "Updated Department Name",
            "description": "Updated Department Description"
        }
        ```

## Technologies Used

- Spring Boot
- Maven
- Postman(For Testing)
- MySql
