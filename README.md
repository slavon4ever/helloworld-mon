# Webapp monitoring with Prometheus & Grafana

## Containers
- Hello-world webapp
    - `https://github.com/slavon4ever/helloworld`
    - `https://hub.docker.com/r/slavon4ever/helloworld`
- Prometheus
- Grafana

## Installation
Clone the project locally to your Docker host.

Run with:

    $ docker-compose up -d

Hello-world webapp is accessible via: `http://<DockerHostIP>:8080`

Webapp metrics: `http://<DockerHostIP>:8080/metrics`

Grafana dashboard: `http://<DockerHostIP>:3000`

        username - admin
        password - 123qwe
