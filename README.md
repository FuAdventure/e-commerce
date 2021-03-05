# E-commerce web application project
This is a full-stack project that builds a shopping website with Angular for the front end and Spring Boot for the back end.

## Website features
- List/detail view of products
- Search for products by category or keyword
- Pagination support for products
- Add, update and remove products in the shopping cart (CRUD)
- Check out forms with content validation
- User authentication based on OAuth 2.0 protocol 

<p align="center">
  <img src="README_images/list.png" width="50%" /> 
  <img src="README_images/search.png" width="50%" />
  <img src="README_images/cart.png" width="75%" />
  <img src="README_images/login.png" width="75%" />
  <img src="README_images/checkout.png" width="75%" />
</p>

## Development enviroment 
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
Run `SpringBootEcommerceApplication.java` to start the server up.
By default the spring boot backend is running at http://localhost:8080/
To view products go to http://localhost:8080/api/products To view product categories go to http://localhost:8080/api/product-categories

- step 3: run angular app </br>
open a new terminal and enter the "frontend" folder
```
ng serve --open
```
This command builds the app, starts the server and open a web browser to http://localhost:4200/



