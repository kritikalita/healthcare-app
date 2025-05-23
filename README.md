# healthcare-app

# JwtUtil - JWT Utility Class in Java (Spring Boot)

This project contains a simple utility class for generating and validating JSON Web Tokens (JWT) using the `io.jsonwebtoken` library in a Spring Boot application.



## Overview

`JwtUtil` is a Spring `@Component` that provides methods to:

- Generate JWT tokens with a username and role claim.
- Validate JWT tokens for authenticity and expiration.
- Extract the username from a valid JWT token.



## Features

- **Token Generation:** Creates a signed JWT with username, user role, issue date, and expiration (1 day).
- **Token Validation:** Checks if a JWT is correctly signed and not expired.
- **Username Extraction:** Retrieves the username (subject) embedded in the JWT.



