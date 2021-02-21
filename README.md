# E-commerce web application project
This is a full-stack project that builds a shopping website with Angular for the front end and Spring Boot for the back end.

## Enviroment 
You should have Node, npm, tsc, Angular CLI, Java Development Kit (JDK), Maven, MySQL installed.

## To run locally
- step 1: prepare database </br>
Run sql scripts in the "db-scripts" folder to build tables.

- step 2: run spring boot app </br>
open a terminal, clone the repository and enter the "backend" folder 
```
./mvnw package
java -jar target/*.jar
```
By default the spring boot backend is running at http://localhost:8080/

- step 3: run angular app </br>
open a new terminal and enter the "frontend" folder
```
ng serve --open
```
This command builds the app, starts the server and open a web browser to http://localhost:4200/



