# Deploying Django to AWS ECS with AWS Copilot

Check out the [tutorial](#).

## Want to use this project?

### Local setup

1. Fork/Clone

1. Build the Docker images:

    ```sh
    $ docker compose -f docker-compose.dev.yml build
    ```

1. Spin up the Docker containers:

    ```sh
    docker compose -f docker-compose.dev.yml up -d
    ```

1. Navigate to [http://localhost:8000/](http://localhost:8000/) in your favorite web browser.

### Deploy to AWS

Check out the [tutorial](#).
