# Spring-Boot-Product-Automation

 Spring Boot Crud Application with Thymeleaf, JPA. 
 
# Product Automation

This project based on the Spring Boot project and uses these packages:

<ul>
<li>Spring Boot</li>
<li>Spring Data</li>
<li>Thymleaf</li>
<li>Bootstrap</li>
<li>Maven</li>
</ul>

## Installation

### 1. Clone the application

<pre> $ git clone https://github.com/batuhaniskr/Spring-Boot-Product-Automation.git </pre>

### 2. Database Configuration

In this project MySQL database is used. db_product.sql file is imported from MySQL.
<ul>
<li> Open src/main/resources/application.properties </li>
<li> Change spring.datasource.username and spring.datasource.password as per your mysql installation</li>
</ul>
The project is created with Maven.

### 3. Build and run the app using maven

<pre>mvn clean install</pre>

<pre>mvn spring-boot:run</pre>

commands run the application.

The application will be start running at http://localhost:8080/products

## Screenshot

![screen shot 2018-01-13 at 19 12 27](https://user-images.githubusercontent.com/17202632/34907839-e475caf4-f895-11e7-89ec-ea32f8560273.png)
