# Tasty Treks

Tasty Treks is a comprehensive online food delivery system designed to revolutionize how users order food. With its user-friendly interface and robust features, it bridges the gap between restaurants and customers, making food delivery seamless and accessible.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Architecture Overview](#architecture-overview)
- [Setup Instructions](#setup-instructions)
- [Advantages](#advantages)
- [Screenshots](#screenshots)
- [Conclusion](#conclusion)

## Introduction
Tasty Treks is a web-based application tailored for food delivery. It enables users to explore diverse restaurant menus, add items to their cart, and securely make payments. The application includes distinct dashboards for users and admins, offering specialized features for both roles.

## Features

- **User/Admin Registration and Secure Login**
  - Supports multi-level authentication for enhanced security.
- **Dashboards**
  - Tailored interfaces for users and admins to streamline navigation.
- **Shopping Cart**
  - Add, view, or remove items conveniently.
- **Payment Gateway Integration**
  - Secure and reliable payment processes.
- **Profile Management**
  - Update profile information and change passwords easily.
- **Admin Management Tools**
  - Add, update, or delete products.
  - Manage user accounts effectively.
- **Order Management**
  - Place, track, or cancel orders with ease.

## Technologies Used

### Front-End
- HTML5, CSS3, Bootstrap 4
- TypeScript and Angular (vX.X for clarity)

### Back-End
- Spring Boot Framework (with Spring Tool Suite)
- MySQL Database
- Testing Tools: Postman, TestNG, Selenium

## Architecture Overview

1. **Registration Management**: Facilitates user and admin registrations.
2. **Authentication System**: Ensures secure login processes.
3. **Cart Management**: Streamlines item selection and modifications.
4. **Payment Gateway**: Integrates secure and efficient payment solutions.
5. **Product Management**: Allows admins to perform CRUD operations on products.
6. **Profile Management**: Offers seamless profile updates and credential management.

## Setup Instructions

### Prerequisites
- [Node.js](https://nodejs.org/) for Angular Front-End
- [MySQL](https://www.mysql.com/) for database management
- [Java JDK](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) for back-end development
- [Spring Tool Suite](https://spring.io/tools) for managing the Spring Boot project

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/tasty-treks.git
   cd tasty-treks
   ```

2. **Back-End Setup**:
   - Import the project into Spring Tool Suite.
   - Configure database credentials in the `application.properties` file.
   - Launch the Spring Boot application.

3. **Database Setup**:
   - Create a MySQL database instance.
   - Execute the SQL script (`schema.sql`) provided to set up the schema and initial data.

4. **Front-End Setup**:
   ```bash
   cd frontend
   npm install
   ng serve
   ```
   - Access the application via `http://localhost:4200`.

5. **Testing and Debugging**:
   - Use Postman to test API endpoints.
   - Run TestNG and Selenium test cases for end-to-end testing.

## Advantages

- **User-Friendly Design**: Intuitive and easy-to-navigate interfaces.
- **Data Security**: Implements industry-standard security measures.
- **Browser Compatibility**: Works seamlessly across major web browsers.
- **Admin Tools**: Provides comprehensive tools for record and user management.
- **Efficiency**: Automates reporting and data storage for faster processes.

## Screenshots
![](https://github.com/MeRishi07/TastyTreks/blob/9c14938e95474c6779d6cdc0eb55d53074f3aa9e/Screenshots/Screenshot%202023-09-26%20001113.png)
![](https://github.com/MeRishi07/TastyTreks/blob/9c14938e95474c6779d6cdc0eb55d53074f3aa9e/Screenshots/Screenshot%202023-09-26%20001128.png)
![](https://github.com/MeRishi07/TastyTreks/blob/9c14938e95474c6779d6cdc0eb55d53074f3aa9e/Screenshots/Screenshot%202023-09-26%20001148.png)
![](https://github.com/MeRishi07/TastyTreks/blob/9c14938e95474c6779d6cdc0eb55d53074f3aa9e/Screenshots/Screenshot%202023-09-26%20001204.png)
![](https://github.com/MeRishi07/TastyTreks/blob/9c14938e95474c6779d6cdc0eb55d53074f3aa9e/Screenshots/Screenshot%202023-09-26%20001236.png)
![](https://github.com/MeRishi07/TastyTreks/blob/9c14938e95474c6779d6cdc0eb55d53074f3aa9e/Screenshots/Screenshot%202023-09-26%20001546.png)
![](https://github.com/MeRishi07/TastyTreks/blob/9c14938e95474c6779d6cdc0eb55d53074f3aa9e/Screenshots/Screenshot%202023-09-26%20001611.png)
![](https://github.com/MeRishi07/TastyTreks/blob/9c14938e95474c6779d6cdc0eb55d53074f3aa9e/Screenshots/Screenshot%202023-09-26%20003423.png)
![](https://github.com/MeRishi07/TastyTreks/blob/9c14938e95474c6779d6cdc0eb55d53074f3aa9e/Screenshots/Screenshot%202023-09-26%20003458.png)
![](https://github.com/MeRishi07/TastyTreks/blob/9c14938e95474c6779d6cdc0eb55d53074f3aa9e/Screenshots/Screenshot%202023-09-26%20003511.png)
![](https://github.com/MeRishi07/TastyTreks/blob/9c14938e95474c6779d6cdc0eb55d53074f3aa9e/Screenshots/Screenshot%202023-09-26%20003604.png)
![](https://github.com/MeRishi07/TastyTreks/blob/9c14938e95474c6779d6cdc0eb55d53074f3aa9e/Screenshots/Screenshot%202023-09-26%20003655.png)
![](https://github.com/MeRishi07/TastyTreks/blob/9c14938e95474c6779d6cdc0eb55d53074f3aa9e/Screenshots/Screenshot%202023-09-26%20004648.png)

## Conclusion
Tasty Treks redefines food delivery with its efficient and secure online system. By combining a robust back-end with a user-focused front-end, it offers a scalable solution for both restaurants and customers, ensuring a superior experience for all stakeholders.
