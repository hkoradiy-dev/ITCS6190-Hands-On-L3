# ITCS 6190 Hands-On L3

## Overview

This hands-on demonstrates how to build and run a multi-container
microservice application using Docker and Docker Compose.

The application consists of:

- A Python Flask web application
- A Redis cache

## Technologies Used

- Docker
- Docker Compose
- Python
- Flask
- Redis

## Project Structure

```text
.
├── app.py
├── Dockerfile
├── compose.yaml
├── requirements.txt
├── README.md
├── .gitignore
└── screenshots/


## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/hkoradiy-dev/ITCS6190-Hands-On-L3.git
cd ITCS6190-Hands-On-L3
```

### 2. Build and Start the Containers

```bash
docker compose up --build
```

### 3. Access the Application

Open a web browser and go to:

```text
http://localhost:5000
```

### 4. Check Running Containers

```bash
docker ps
```

### 5. Stop the Application

```bash
docker compose down
```

## What I Learned

I learned how to use Docker to containerize a Flask application and how to use Docker Compose to run multiple services together.

I also learned how a Flask web application can communicate with a Redis container and how Docker Compose manages the services and their networking.

Finally, I learned how to troubleshoot Docker, Git, and application errors and document the errors and their solutions.

## Screenshots and Report

Screenshots and the final report are included in the `screenshots/` directory.
