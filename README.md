# E-commerce web application project
This is a full-stack project that builds a shopping website with Angular for the front end and Spring Boot for the back end.

# Enviroment 
You should have node, npm, tsc, Angular CLI, mySQL installed.

# Running locally
step 1: prepare database
Run sql scripts in the "db-scripts" folder to build tables.

step 2: run spring boot app
open a terminal, clone the repository and enter the "backend" folder 
```
./mvnw package
java -jar target/*.jar
```
By default the spring boot backend is running at http://localhost:8080/

step 3: run angular app
open a new terminal and enter the "frontend" folder
```
ng serve --open
```
This command builds the app, starts the server and open a web browser to http://localhost:4200/



