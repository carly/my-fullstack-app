# Server

This directory contains the server-side code of the application, which is built with Python, FastAPI, GraphQL, and PostgreSQL.

## Getting Started

To start the server, you need to have Docker installed. Run the following command:

```bash
docker-compose up
```

This will start the server at `http://localhost:8000`.

## Directory Structure

- `app/main.py`: The entry point of the FastAPI application.
- `app/models`: Contains the database models.
- `app/schemas`: Contains Pydantic schemas.
- `app/api`: Contains the API routes.
- `app/db`: Contains the database configuration and utilities.
- `tests`: Contains the tests for the application.
- `Dockerfile`: Contains the Docker instructions to build the server image.
- `requirements.txt`: Lists the server-side dependencies.

## Testing

To run the tests, use the following command:

```bash
docker-compose run server pytest
```

## API Documentation

FastAPI automatically generates API documentation. After starting the server, you can access the documentation at `http://localhost:8000/docs`.

## Database

The application uses PostgreSQL as the database. The configuration can be found in the `app/db` directory.

## Dependencies

The server-side dependencies are listed in the `requirements.txt` file. To add a new dependency, add it to this file and rebuild the Docker image.

## Docker

The `Dockerfile` contains the instructions to build the Docker image for the server. The `docker-compose.yml` file in the root directory is used to start the server and the database.