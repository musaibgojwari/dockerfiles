# Simple Docker File

This is a simple project for testing Docker functionality. It includes a Dockerfile that sets up a basic environment and runs a Python script (`app.py`) as a test application.

## Getting Started

These instructions will help you set up and run the project on your local machine.

### Prerequisites

- [Docker](https://www.docker.com/get-started)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/your-repository.git
    ```

2. Navigate to the project directory:

    ```bash
    cd your-repository
    ```

3. Build the Docker image:

    ```bash
    docker build -t your-image-name:tag .
    ```

### Usage

Run a Docker container based on the built image:

```bash
docker run your-image-name:tag
```

## Additional Docker Commands

### List Docker Images

To see the Docker images on your system, run:

```bash
docker images
```

List Running Containers
To view the running Docker containers, use:

```bash
docker ps
```

List All Containers
To view all Docker containers (including stopped ones), use:

```bash
docker ps -a
```

