# Trello API Testing 

Manual API testing project for Trello REST API using Postman.

## Overview

Demonstrates manual testing of the following endpoints:

- GET /members/me/boards
- POST /boards
- PUT /boards/{id}
- DELETE /boards/{id}

The goal is to ensure that all endpoints work correctly, returning accurate data.

## Authentication

Requests require:

- API Key ('key')
- API Token ('token')

They are passed as query parameters:

https://api.trello.com/1/members/me/boards?key={{myKey}}&token={{myToken}}

The collection validates:
- Authentication (API key & token)
- HTTP status codes
- Response structure
- Required JSON fields

## Tools Used

- Postman
- Trello REST API
- GitHub

API Testing | Postman | Functional Testing
