Only of Localhost - http://localhost:8080/EmployeePortal/
EmployeePortal

EmployeePortal is a Java-based Employee Management Web Application developed using JSP, Servlets, and JDBC. The application runs on Apache Tomcat and connects to a relational database (MySQL) to manage employee records efficiently.

This project follows the MVC (Model-View-Controller) architecture to maintain proper separation of concerns. JSP pages handle the presentation layer, Servlets manage the business logic and request handling, and the DAO layer manages database interactions using JDBC.

Features

Employee Registration with database insertion

Secure Login Authentication using JDBC validation

Employee Dashboard to display user details

Error handling for invalid login attempts

Clean separation of Model, View, and Controller layers

Application Flow

When a user registers, the form data is sent to a Servlet, which creates an Employee object and passes it to the DAO layer for database insertion. During login, the Servlet validates credentials by querying the database. If authentication is successful, the user is redirected to the dashboard page; otherwise, an error page is displayed.

Technologies Used

Core Java

JSP (Java Server Pages)

Servlets

JDBC

MySQL

Apache Tomcat

HTML & CSS

Key Learning Outcomes

Implementation of MVC architecture in Java web applications

Handling HTTP requests and responses using Servlets

Database connectivity using JDBC and PreparedStatement

Session handling and authentication logic

Deployment and execution on Apache Tomcat server

This project demonstrates strong fundamentals in Java web development, backend processing, and database integration without using frameworks like Spring, making it a solid foundation-level full stack application.
