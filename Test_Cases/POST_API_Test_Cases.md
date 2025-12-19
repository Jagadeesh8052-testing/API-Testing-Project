# POST API Test Cases – E-commerce REST APIs

## POST /users

1. Verify user creation with valid payload returns status code 201.
2. Verify response body contains created user id.
3. Verify response Content-Type is application/json.
4. Verify error response when mandatory fields are missing.
5. Verify error response for invalid email format.

## POST /auth/login

6. Verify login with valid username and password returns status code 200.
7. Verify login response contains authentication token.
8. Verify token value is not null.
9. Verify login with invalid credentials returns status code 401.
10. Verify proper error message for invalid login.
