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


