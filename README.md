# Trello API Testing 

Manual API testing project for Trello REST API.

## Project Overview

This project demonstrates manual testing of the following endpoints:

GET/POST/DELETE/PUT

The goal is to ensure that all endpoints work correctly, returning accurate data.

## Authentication

Requests require:

- API Key ('key')
- API Token ('token')

They are passed as query parameters:

https://api.trello.com/1/members/me/boards?key={{myKey}}&token={{myToken}}

## What Was Tested

- Authentication behavior
- HTTP status codes
- Response time
