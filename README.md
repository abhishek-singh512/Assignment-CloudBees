# Assignment-CloudBees
```
To fulfill the requirements and implement the project using Java Spring Boot, Postman for API 
testing, and MySQL for databases, you'll need to follow several steps. Below is an outline of how you can approach this task:
```
### Setup Development Environment:
```
Install Java Development Kit (JDK) and Apache Maven.
Set up MySQL and create a database for the project.
Install and configure Spring Boot.
```
### Create a Spring Boot Project:
```
Use Spring Initializr to create a new Spring Boot project with necessary dependencies 
such as Spring Web, Spring Data JPA, and MySQL Driver.
```
### Define Entity Classes:
```
Create entity classes such as User and Ticket to represent the data model.
Define relationships between entities if needed (e.g., User has a Ticket).
```
### Implement Controllers:
```
Create controllers to handle HTTP requests and define APIs.
Implement endpoints for purchasing a ticket, viewing receipt details, viewing users and their seats, removing a user, and modifying a user's seat.
```
### Implement Service Layer:
```
Create service classes to encapsulate business logic.
Implement methods to handle ticket purchase, user management, and seat allocation.
```
### Implement Persistence Layer:
```
Use Spring Data JPA to interact with the database.
Define repositories for entities to perform CRUD operations.
```
### Test with Postman:
```
Use Postman to test the implemented APIs.
Verify that the endpoints behave as expected and handle various scenarios.
```
## #Configure MySQL:
```
Update application.properties with MySQL database connection details.
Configure Hibernate dialect and other properties.
```
### Publish to GitHub:
```
Create a public repository on GitHub.
Push the codebase to the repository.
Ensure that the README.md file contains instructions for setting up and running the project.
```

![IMG_20240316_224831-transformed](https://github.com/abhishek-singh512/Assignment-CloudBees/assets/118076036/ead01bd6-8b1c-44bd-b748-9989dc2850ad) 
### --------------------------------------------------------------------------- ###
![IMG_20240316_224905](https://github.com/abhishek-singh512/Assignment-CloudBees/assets/118076036/6c07d5df-7b2a-49df-aaa2-9bdacf18fc3f)
### --------------------------------------------------------------------------- ###
![screenshot](https://github.com/abhishek-singh512/Assignment-CloudBees/assets/118076036/a155054d-8b91-4097-ab14-3fb2de918d9e)
### --------------------------------------------------------------------------- ###
```
1.I want to board a train from London to France. The train ticket will cost $20.
2.Create API where you can submit a purchase for a ticket. Details included in the receipt are:
3.From, To, User , price paid.
4.User should include first and last name, email address
5.The user is allocated a seat in the train. Assume the train has only 2 sections, section A and section B.
6.An API that shows the details of the receipt for the user.
7.An API that lets you view the users and seat they are allocated by the requested section
8.An API to remove a user from the train
9.An API to modify a user's seat
```
### --------------------------------------------------------------------------- ###
![Screenshot (1885)](https://github.com/abhishek-singh512/Assignment-CloudBees/assets/118076036/7cbf03ec-2744-4d54-8b5d-1b18223f01fc)
### --------------------------------------------------------------------------- ###
![Screenshot (1886)](https://github.com/abhishek-singh512/Assignment-CloudBees/assets/118076036/7b49cfbc-c8fb-4662-bf9b-e81235f5e538)

### -------------------------- Databases Implementation ........................###
![Screenshot (1890)](https://github.com/abhishek-singh512/Assignment-CloudBees/assets/118076036/564f8fd0-b166-4dc1-9648-4678f4593adb)

### --------------------------------------------------------------------------- ###

Overall, by following these guidelines and continuously striving for improvement, we can develop the train ticket booking application API in the best possible way, meeting the requirements 
effectively and delivering value to users and stakeholders.
