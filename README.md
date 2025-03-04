# Jira + Jenkins Docker Compose Setup

## Prerequisites

- Docker
- Docker Compose

## Services

- **Jira** (Atlassian Jira Software)
- **PostgreSQL** (Database for Jira)
- **Jenkins** (CI/CD Automation Server)

## Usage

1. Clone this repository:
   ```sh
   git clone <repo-url>
   cd <repo-folder>
   ```
2. Start the containers:
   ```sh
   docker-compose up -d
   ```
3. Access the services:
   - Jira: [http://localhost:8080](http://localhost:8080)
   - Jenkins: [http://localhost:8081](http://localhost:8081)

## Configuration

- Jira database settings:
  - Host: `postgres`
  - User: `jira`
  - Password: `jira`
  - Database: `jiradb`

## Stopping the Services

To stop the containers, run:

```sh
docker-compose down
```

## License

This project is open-source under the MIT License.

