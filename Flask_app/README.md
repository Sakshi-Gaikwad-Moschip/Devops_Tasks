# Simple Flask App in Docker

A tiny Flask web app containerized with Docker.

## Run it with Docker

```bash
docker build -t flask-app .
docker run -d -p 5000:5000 flask-app