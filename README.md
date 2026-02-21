# WordPress Docker Microservices Project

A multi-container WordPress setup using Docker Compose with a microservices architecture.

## Architecture

- **MySQL** - Database container
- **WordPress** - Backend container (PHP-FPM)
- **Nginx** - Frontend reverse proxy container

## Project Structure
```
wordpress-docker/
├── .env
├── .gitignore
├── docker-compose.yml
├── nginx/
│   └── nginx.conf
└── README.md
```

## Prerequisites

- Docker
- Docker Compose

## Setup & Run

1. Clone the repo
```bash
   git clone https://github.com/maximumincome/word-press-project.git
```

2. Create your `.env` file
```bash
   cp .env.example .env
```

3. Run the containers
```bash
   docker compose up -d
```

4. Open browser at `http://localhost:8181`

## Stopping the project
```bash
docker compose down
```

## Author

Maxwell