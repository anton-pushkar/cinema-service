# 🎦 Cinema-Service 🎦
# Project description
Simple REST API of cinema service for ordering tickets that supports db authentication, registration and other CRUD operations.
# Features
For users
- complete an order
- create shopping cart
- add tickets to shopping cart
- registration or login as user
- find user by email(only for Admin)
- get order history for current user
- delete movie-sessions(only for Admin)
- create(only for Admin) and find movies
- create(only for Admin) and find available movie-sessions
# Project structure
Project uses 3-tier architecture:
1. Data access tier -> handled by DAO;
2. Business logic tier -> handled by Service;
3. Presentation tier -> handled by Controllers and Spring.
<img src="img.png">

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
2. Configure connection to your database in
> [cinema-app/src/main/resources/db.properties]

By changing driver, url to your database, username and password to your own. <br/>

3. Build project
```shell
mvn clean package
```

4. Run this in server. I am using Tomcat 9.0.50. <br/>
