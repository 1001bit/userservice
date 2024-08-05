# User Microservice

### A service, that provides simplest user authentication
#
Provides user with fields: Username, registration date, hash

Make sure, that environment variables are set (see .env.example)

Uses gRPC for inter-microservice communication (pkg/userpb/user.proto)

Uses postgresql as database (see init.sql). Make sure that one is configured and running

Uses bcrypt for hash generation

