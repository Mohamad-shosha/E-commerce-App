# E-commerce Project with Spring Boot

Welcome to our **E-Commerce** App! This application is built using Spring Boot and Java, serving as the backend for our online store. This README file provides an overview of the application, its features, Prerequisites, Demo, Resourses and Technologies.

## 📝Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Note](#Note)
- [Postman testing](#Postman-Testing)
- [Technologies](#Technologies)
- [Demo](#Demo)
- [Resourses](#Resourses)
  
## 🚀Features

- **Product Listing**: View available products with details.
- **Order Viewing**: View previous orders and order details.

---
## 📖prerequisites
Before you begin, ensure you have met the following requirements:

- Java Development Kit (JDK) installed.
- Maven installed.
- Your favorite IDE (e.g., IntelliJ, Eclipse) for code editing.

---
## ✨Getting Started

Step 1: Create a Spring Boot Project
You can use Spring Initializr to generate a basic Spring Boot project. Visit [start.spring.io](https://start.spring.io/;) and configure your project with the following settings:

* Project: Maven Project
* Language: Java
* Spring Boot: Latest stable version
* Packaging: Jar
* Dependencies: Spring Web , Spring Data JPA , devtools , thymeleaf , data-jpa , security , mysql-connector-j and plugin.
Click on "Generate" to download the project zip file.

Step 2: Extract and Import into IDE
Extract the downloaded zip file and import the project into your preferred IDE (IntelliJ IDEA, Eclipse, etc.).

Step 3: Define Entity
Create a simple entity class representing the object you want to manage. For example, if you are building a E-commerce application for , create a products and product-category classes , and this varies according to your project and its dependence on the entites and relationships in the data base .

Step 4: Create Repository
Create a repository interface for your entity to perform CRUD operations.

Step 5: Create Controller
Create a controller to handle HTTP requests and interact with the repository.

## Note 🚫
This E-Commerce application operates in a read-only mode. It does not support PUT, POST, or DELETE operations. It is designed solely for viewing products, orders, and inventory. Thank you for your understanding. 🛍️


## Postman-Testing
To test the API endpoints using Postman, follow these steps:
1. **Import Postman Collection**: 
- Import the provided Postman collection file `ecommerce_app.postman_collection.json`.
2. **Set Environment Variables**:
- Create a new environment in Postman.
- Set the `base_url` variable to `http://localhost:8080`.
3. **Test Endpoints**:
- Use the imported collection to test various endpoints like retrieving products, viewing orders, etc.

---
## 📚Technologies

* IntelliJ IDEA Community Edition 2023.1.3
* mysQL Workbench 8.0 CE
* postman
---
## 🎥Demo

https://github.com/Mohamad-shosha/E-commerce-App/assets/150439621/d12513f6-3e75-414b-987e-0cb9579b9c30


---
## 🗂️Resourses
* [Spring boot](https://spring.io/why-spring)
* [Spring boot tutorial](https://spring.io/guides/gs/spring-boot)
* [Professor chad darpy](https://luv2code.com/)

---
