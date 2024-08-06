# PostgreSQL
PostgreSQL Docker image

### Start
    docker run --name postgresql -p 5432:5432 -e POSTGRES_PASSWORD=1234 postgres
    docker run --name postgresql -p 5432:5432 -e POSTGRES_PASSWORD=1234 -v /tmp/database:/var/lib/postgresql/data postgres
