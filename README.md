

# RESTful API for social

This project is a RESTful API for a social application, which includes basic functions such as user authentication, registration, getting user information, getting a list of online users, creating groups, adding and removing users from a group, creating posts, and updating/deleting posts.

## Technologies Used
- Spring Boot
- Spring Security
- JSON Web Tokens
- MySQL
- Redis
- MongoDB
- Spring Data JPA
- JDK 11

## Getting Started
To use this application, follow these steps:

1. Clone the repository:

```
git clone https://github.com/LaiHuuMinh/Project_spring_security_socical.git
```

2. Open the project in your preferred IDE.

3. Set up the necessary databases (MySQL and Redis). You can find the database configurations in the `application.properties` file.

4. Run the application.

## Endpoints

- POST  : Sign up for a new account.
- POST  : Sign in to an existing account.
- GET   : Get user information by ID.
- GET  : Get a list of online users.
- POST  : Create a new group.
- GET  : Get group information by ID.
- POST  : Add a user to a group.
- DELETE  : Remove a user from a group.
- POST : Create a new post.
- PUT  : Update a post by ID.
- DELETE : Delete a post by ID.

## Contributors
- Lai Huu Minh

 
