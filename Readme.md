# Reelo Assignment - Project Setup

This project is a web application built as part of an assignment for Reelo. The project consists of a Node.js backend and a React frontend. Docker Compose is used to set up the development environment with separate containers for the backend and frontend.

## Prerequisites

Make sure you have the following installed on your local machine:

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)


- **backend/**: Contains the Node.js backend code.
- **frontend/**: Contains the React frontend code.
- **docker-compose.yml**: Configuration file for Docker Compose.

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/dojeto/reelo-task.git
cd reelo-task
```

### 2. Environment Variables

```
PORT=3000
DB_CONNECTION_STRING=your_database_connection_string
JWT_SECRET=your_jwt_secret
```

```
VITE_BACKEND_URL=http://localhost:3000
PORT=3000
```


### 2. Build and Run the Application
```
docker-compose up --build
```
