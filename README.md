# Spring Boot Mail Schedule with Quartz Scheduler

This is a simple Demo

### Stack
1. Spring Data JPA
2. Quartz
3. Web
4. Jetty Server
5. MySQL

## Installation

1. Edit your application.properties on MySQL Connection
3. Put quartz_table.sql into your MySQL database
4. Login into Mailtrap.io and create your inbox, paste your host, username, password into application.properties
4. Run your app with
```bash
mvn spring-boot:run
```

![Screenshot](postman.png)
![Screenshot](mailtrap.png)