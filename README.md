[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/NkrcaSS8)

# API GATEWAY - HOMEWORK #

## Who am I? ##

* Name: Fernando Murillo Noya
* Group: 1

## How to? ##

Run this command:

```
docker compose up
```

### Endpoints ###

For authentication use this endpoint:

* POST http://localhost:9000/auth/login

Use these credentials:

```
username=validUser
password=validPassword
```

For revision of API Gateway functionality, use these endpoints:
* GET http://localhost:9000/api/users
* GET http://localhost:9000/api/posts

In both cases it is necessary to use Bearer Token with the token created in authentication endpoint.

### Repositories and others ###

If needed to review source code, refer to this [repo](https://github.com/fernandomn1983/api-gateway-spring-cloud-gateway).

Also, in this repository you can find the postman collection used for this API Gateway.
