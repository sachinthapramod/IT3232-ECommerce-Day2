# IT3232-ECommerce-Day2

# Introduction to Spring Boot

Spring Boot is a powerful framework built on top of the Spring Framework that simplifies the development of Java applications, especially web applications. One of its key features is its seamless integration with the Model-View-Controller (MVC) architecture, which is widely used for developing scalable web applications.



# What is Spring Boot MVC?
Spring Boot MVC is an implementation of the traditional Spring MVC framework but with auto-configuration, embedded servers, and minimal setup. It follows the MVC design pattern, which separates the application into three main components:

✅ Model (M) → Represents the data and business logic.

✅ View (V) → Handles UI and presentation (e.g., HTML, Thymeleaf).

✅ Controller (C) → Manages the request processing and interacts with Model and View.

This separation makes the application more maintainable and scalable.



# How Spring Boot Works with MVC
1️⃣ Client (Browser/Postman) sends an HTTP request.

2️⃣ DispatcherServlet (Front Controller) receives the request.

3️⃣ It maps the request to an appropriate Controller using @RequestMapping.

4️⃣ The Controller interacts with the Model (business logic/database).

5️⃣ The Controller returns data to the View (e.g., HTML, JSON, Thymeleaf).

6️⃣ The response is sent back to the client.



## Spring Tools for Eclipse - Installation Guide

Spring Tools (Spring Tool Suite - STS) is an Eclipse-based IDE designed for developing Spring Boot applications efficiently.


1️⃣ Visit the official Spring Tools website:
🔗 https://spring.io/tools

2️⃣ Download Spring Tools 4 for Eclipse (suitable for your OS: Windows, macOS, or Linux).
