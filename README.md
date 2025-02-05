# DevOps - Containerization of Java Project using Docker

![Project Architecture](Containerization%20of%20Java%20Project%20using%20Docker.png)

## Overview
This project demonstrates the **containerization** of a **Java-based web application** using **Docker** and **Docker Compose**. The goal is to simplify deployment, improve scalability, and maintain a consistent runtime environment.

## Steps Involved:
1. Choose a base image from **Docker Hub**.
2. Write a **Dockerfile** to customize the image.
3. Use **docker-compose.yml** to define multi-container services.
4. Test the setup locally.
5. Push the Docker image to **Docker Hub**.
6. Deploy the containerized app.

## Files Included:
- `docker-compose.yml` - Defines multi-container setup.
- `Dockerfile` - Builds the custom application image.
- `pom.xml` - Maven build configuration.
- `src/` - Source code for the application.

## How to Run:
```bash
docker-compose up -d



# Prerequisites
#
- JDK 11 
- Maven 3 
- MySQL 8

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- Rabbitmq
- ElasticSearch
# Database
Here,we used Mysql DB 
sql dump file:
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql


