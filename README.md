Labor Optimization & Pacing Dashboard
A real-time facility operations control dashboard designed to monitor sort pacing, calculate bottom-up belt staffing, and prevent labor leaks.

The Business Case
In a fast paced logistical environment, managers need visibility in every area so they can make necessary adjustments.
This staffing system aims to help managers see their staffing levels in every part of the operation floor to reduce Total
Labor Hours, as well as ensure a smooth  and safe sort/operation. 

Core Features

* Dashboard layout: Easy to view interface designed for the facility floor.
* Color-coded health signals: Flashing red indicates labor is not optimized, while green indicates staffing is balanced.
* Generates recommendations: Automatically calculates required headcount based on changing operational data.
* Interactive manual input: Receives user input to mimic the workflow of live API data feeding into the system.
* Real-time labor variances: Compares dynamic volume against the target PPH to identify exact locations of labor leaks.

ech Stack

* Phase 1 (Prototype): Vanilla HTML, CSS, JavaScript
* Phase 2 (Enterprise Backend): Java 21, Spring Boot, Spring Data JPA, H2 In-Memory Database, Maven

  Execution Instructions

Phase 1: Local HTML Prototype

1. Clone or download this repository.
2. Navigate to the `/resources/static` folder.
3. Double-click `index.html` to run the dashboard directly in your web browser (no server installation required).

**Phase 2: Enterprise Spring Boot**

1. Ensure Java 21 is installed on your local machine.
2. Open the project directory in IntelliJ IDEA.
3. Allow the Maven wrapper to sync the required dependencies.
4. Run `LaborOptimizationApplication.java` to start the local Tomcat server.
5. Navigate to `http://localhost:8080` to view the live application and database connection.

