1. What was the most challenging part of building this boilerplate?
The most challenging part was configuring TypeORM and connecting it to the database. I overcame it by troubleshooting errors and checking my configuration step by step.

2. How does this boilerplate differ from your Midterm project?
My boilerplate has a more organized structure with separate controllers, services, and routes. I also added Joi validation, centralized error handling, Winston logging, and migrations.

3. Why is centralized error handling better than try-catch in every controller?
It avoids repeating the same code in every controller. It also makes error handling easier and more consistent.

4. How does Joi validation improve security and code quality?
Joi checks user input before processing it. It helps prevent invalid data and reduces errors in the application.

5. What's the difference between synchronize: true and migrations?
synchronize: true automatically updates database tables, while migrations manage database changes through files. Migrations are safer for production because they give us control over database changes.

6. How does Winston help compared to console.log?
Winston organizes logs by levels, such as errors and warnings. It also saves logs, making debugging easier in production.

7. How would you add a Product CRUD feature?
I would create a Product entity, service, controller, routes, and validation. I would also create a migration to add the Product table to the database.

8. What additional features would you add?
I would add JWT authentication, password hashing, rate limiting, and unit testing. These features would make the application more secure and reliable.


Activity 9

1. Project Description
This project is a backend boilerplate with user authentication and organized API structure. It includes registration, login, JWT authentication, validation, and error handling.

2. Authentication Flow Documentation
Users register an account and log in using their email and password. After successful login, the system generates a JWT token for accessing protected endpoints.

3. How to Get a Token
Send a POST request to /api/auth/login with your email and password. If the credentials are correct, the server returns an authentication token.

4. How to Use the Token
Copy the JWT token and include it in the request header as Authorization: Bearer YOUR_TOKEN. This allows you to access protected endpoints.

5. Public vs. Protected Endpoints
Public: Register, login, and other endpoints that do not require authentication.

Protected: User profile and other endpoints that require a valid JWT token.

6. Reflection
Building this project helped me understand how authentication works and how to protect API endpoints. I also learned how to organize backend code and handle errors and validation properly.


