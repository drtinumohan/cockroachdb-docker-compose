## Steps
    docker network create -d bridge cockroachdb_net ( create network)
    docker-compose up --build
    docker ps
    docker exec -it node_1 ./cockroach init --insecure
    docker exec -it node_1 /bin/bash
    ./cockroach sql --insecure
    CREATE DATABASE some_db;
    finally:
    ip_address:8080 (example:0.0.0.0:8080 , check the db clusters and nodes)
