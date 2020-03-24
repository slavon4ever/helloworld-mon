# Webapp monitoring with Prometheus & Grafana

## Installation
Clone the project locally to your Docker host.

Run with:

    $ docker-compose up -d

Hello-world webapp is accessible via: `http://<DockerHostIP>:8080`

Webapp metrics: `http://<DockerHostIP>:8080/metrics`

Grafana dashboard: `http://<DockerHostIP>:3000`

        username - admin
        password - 123qwe
