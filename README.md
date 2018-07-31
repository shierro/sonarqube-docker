## Sonarqube docker-compose
  - Run sonarqube inside a docker container and persist data on host folder

### Usage
```bash
export POSTGRES_USER=postgres
export POSTGRES_PASSWORD=postgres
export POSTGRES_URL=localhost:5432
docker-compose up
```

### don't have an existing postgres instance? Use sonar-postgres.yml!
```bash
export POSTGRES_USER=postgres
export POSTGRES_PASSWORD=postgres
docker-compose -f sonar-postgres.yml up -d
```
