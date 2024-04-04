# My Fullstack App

This is a fullstack application built with React, TypeScript, Tailwind CSS on the frontend, and Python FastAPI, GraphQL, and PostgreSQL on the backend. The application is containerized using Docker.

## Project Structure

The project is divided into two main parts: the `client` and the `server`.

### Client

The `client` directory contains the frontend of the application built with React, TypeScript, and Tailwind CSS. The main entry point of the application is `src/index.tsx` which renders the `App` component.

### Server

The `server` directory contains the backend of the application built with Python FastAPI. The main entry point of the application is `app/main.py`.

## Setup and Installation

Ensure you have Docker and Docker Compose installed on your machine.

To start the application:

1. Clone the repository
2. Navigate to the project directory
3. Run `docker-compose up`

This will start the frontend and backend services as defined in the `docker-compose.yml` file.

## Testing

To run tests on the server, navigate to the `server` directory and run `python -m unittest`.

## Contributing

Please read `CONTRIBUTING.md` for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.