# TAXI-SERVICE
 _______________
## Description :
A simple implementation of the taxi-service web application, which includes registration, authorization and CRUD operation with entities
## Features :
+ registration as a driver
+ authentication as a driver
+ create/update/remove a manufacturer
+ create/update/remove a car
+ add driver to car
------------------
## Technologies:
+ JDK 11
+ Maven 4.0.0
+ MySQL 8.0.24
+ TomCat 9.0.70
+ JSP
+ HTML/CSS
+ Javax-servlet 4.0.1
+ JSTL
-------------------
## Start the program:
+ Install JDK
+ Install Tomcat server
+ Clone the project from GitHub
+ Configure ConnectionUtil class with your URL, USER_NAME, PASSWORD, JDBC_DRIVER;
+ Add new run configuration on Intellij IDEA -> go to Edit configuration -> Add new ->
    -> Tomcat server -> Local -> Fix -> Select "taxi-service:war-exploded" ->
    -> in application context save only "/"