# 🎦 Cinema-Service 🎦
# Project description
REST API of cinema service for ordering tickets that supports authentication, registration and other CRUD operations.
# Features
For users
- find movies
- complete an order
- find available movie-sessions
- create shopping cart
- add tickets to shopping cart
- registration or login as user
- get order history for current user

For admin
- create movie
- find user by email
- create, delete movie-sessions
# Project structure
Project uses 3-tier architecture:
1. Data access tier -> handled by DAO;
2. Business logic tier -> handled by Service;
3. Presentation tier -> handled by Controllers.

A diagram of my models
<img src="pictures/img.png">
# Technologies
- Maven
- JDK 11
- JDBC
- Spring-Core
- Spring-Web
- Spring-Security
- Hibernate
- Tomcat 9.0.50
- MySQL 8.0
# Instructions to run my project
1. Clone this repository <br/>
2. Configure connection to your database in ["db.properties"](src/main/resources/db.properties)

By changing driver, url to your database, username and password to your own. <br/>

3. Build project
```shell
mvn clean package
```

4. Run this in server. I am using Tomcat 9.0.50. <br/>
*You have default admin (login: admin, pass: admin)*
