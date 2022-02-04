msngr-j
=====

A sample web application in Java using the Spring Boot Framework.

Requirement 
============

* JDK 1.8 or later
* Gradle 4

Run
===

`./gradlew bootRun` or the "Run" task in IntelliJ IDEA

Layout
=====
Create new post (if logged in)
* `http://localhost:8080`

View post history
* `http://localhost:8080/history`

Health check (for running in e.g. Docker) 
* `http://localhost:8080/actuator/health`


How To
=====
Create Table for logger
* `create table SptringBootTable(timeStamp DATE, line VARCHAR(50));`

Credits
=====
Original Code - Ilia Zlatkin
Improvements - Darin Debrestian
