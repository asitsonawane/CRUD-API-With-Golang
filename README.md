# Simple CRUD API With Golang

A simple Go web application for managing a list of movies.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This Go application provides a basic API for managing a list of movies. It uses the Gorilla Mux router for handling HTTP requests and JSON encoding/decoding for data storage.

## Features

- List all movies
- Get a specific movie by ID
- Add a new movie
- Update an existing movie
- Delete a movie by ID

## Installation

To run this application, you'll need Go installed on your machine.

1. Clone the repository:

```bash
git clone https://github.com/yourusername/simple-movie-api.git
```

2. Navigate to the project directory:
```bash
cd simple-movie-api
```

3. Start the server:
```bash
go run main.go
```

The server will start on port 8000.

# Usage
Once the server is running, you can use any HTTP client (such as Postman or cURL) to interact with the API.

## Example Requests

- Get all movies:
```
GET http://localhost:8000/movies
```

- Get a specific movie:
```
GET http://localhost:8000/movies/{id}
```

- Update a movie:
```
PUT http://localhost:8000/movies/{id}
```

- Delete a movie:
```
DELETE http://localhost:8000/movies/{id}
```

## API Endpoints

- GET /movies - Retrieve a list of all movies
- GET /movies/{id} - Retrieve a specific movie by ID
- POST /movies - Add a new movie
- PUT /movies/{id} - Update an existing movie
- DELETE /movies/{id} - Delete a movie by ID