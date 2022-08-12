# :ticket:Cinema Project:ticket:
![Teaser-Cinema-1200-500](https://user-images.githubusercontent.com/99022808/184300373-2fe103f0-a288-495e-842f-422c3082e160.jpg)
## Description
This application simulates cinema's ticket-reservation system and has next functions:
* Register a new user
* Login
* Authorization based on roles
* basic CRUD operations, which you can check on the next endpoints:
```
[POST]   /register - registers a new user
[POST]   /cinema-halls - creates a new cinema hall
[GET]    /cinema-halls - returns all cinema halls
[POST]   /movies - creates a new movie
[GET]    /movies - returns all movies
[POST]   /movie-sessions - creates a new movie session
[GET]    /movie-sessions/available - returns all available movie sessions for the selected movie
[PUT]    /movie-sessions/{id} - updates a movie session
[DELETE] /movie-sessions/{id} - deletes a movie session
[POST]   /orders/complete - completes an order
[GET]    /orders - returns order history of user
[PUT]    /shopping-carts/movie-sessions - adds a movie session to shopping cart
[GET]    /shopping-carts/by-user - returns shopping cart of logged user
[GET]    /users/by-email - returns user by email
```
##Project architecture
* DAO - Data access layer
* Service - Application layer
* Model - Presentation layer
## Database structure
![Diagram](https://user-images.githubusercontent.com/99022808/184330308-e993e9d2-e28d-4cc8-b454-3cb3fadfed1a.png)

## Technologies used in project
* Java 11
* Hibernate
* Spring (Core, Web, Security)
* MySQL
* Apache TomCat 
* Maven
## Setup
