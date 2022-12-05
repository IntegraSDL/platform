# platform

## Setting up environment variables

Before running docker compose you should set up `.env` file in main directory with all variables below.

### Gitea postgress database

Example:

```bash
POSTGRES_HOST=gitea-db:5432
POSTGRES_DB_NAME=gitea
POSTGRES_USER=postgres
POSTGRES_PASS=postgres
```

### Drone

Example:

```bash
DRONE_RPC_HOST=drone
DRONE_RPC_PROTO=http
DRONE_RPC_SECRET=secret
DRONE_UI_USERNAME=test
DRONE_UI_PASSWORD=test
DRONE_DEBUG=true
DRONE_TRACE=true
DRONE_LOGS_DEBUG=true
```

### Restic password

Example:

```bash
RESTIC_PASSWORD=test
```