# User Microservice

### A service, that provides simplest user authentication

Provides user with fields: Username, registration date, hash

## Technologies used:

Uses gRPC for inter-microservice communication (pkg/userpb/user.proto)

Uses postgresql as database (see init.sql).

Uses bcrypt for hash generation

## Building and running:

- Make sure, that environment variables are set (see .env)
- To Build: `make build`
- To Run: `make up`