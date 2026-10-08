# Session 09 - Exercise 5

## Docker Compose

File: docker-compose.yml

    services:
      web:
        image: nginx:alpine
        ports:
          - "8082:80"

## Start service

    docker compose up -d

## Check service

    docker compose ps

## Test

    curl.exe http://localhost:8082

Expected result: Nginx Welcome page.

## Stop service

    docker compose down