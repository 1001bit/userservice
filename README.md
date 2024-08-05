# User Microservice

### A service, that provides simplest user authentication
#
Provides user with fields: Username, registration date, hash

Uses gRPC for inter-microservice communication (pkg/userpb/user.proto)

Uses postgresql as database (see init.sql)

Uses bcrypt for hash generation

Make sure, that environment variables are set (see .env.example)