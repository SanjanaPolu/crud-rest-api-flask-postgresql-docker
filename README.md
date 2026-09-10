# CRUD REST API using Flask, SQLAlchemy, PostgreSQL & Docker

## Project Overview

This project is a RESTful CRUD API developed using Python Flask, SQLAlchemy, and PostgreSQL. The application is containerized using Docker and Docker Compose for easy setup and execution.

The API allows users to be created, viewed, updated, and deleted through standard HTTP methods.

## Technologies Used

- Python
- Flask
- SQLAlchemy
- PostgreSQL
- Docker
- Docker Compose
- Postman

## Features

- Create a new user
- Retrieve all users
- Retrieve a user by ID
- Update user details
- Delete a user
- PostgreSQL database integration
- Dockerized application
- API testing using Postman

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/users` | Create a new user |
| GET | `/users` | Retrieve all users |
| GET | `/users/<id>` | Retrieve a user by ID |
| PUT | `/users/<id>` | Update user details |
| DELETE | `/users/<id>` | Delete a user |

## Project Structure

flask-crud-live/
├── app.py
├── Dockerfile
├── docker-compose.yml
└── requirements.txt
