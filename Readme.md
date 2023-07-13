# Buildkite Python Docker Example (using pipenv)

This repository is an example on how to test a [Python](https://python.org) project using [Docker](https://www.docker.com/) and [pipenv](https://github.com/kennethreitz/pipenv).

## How does it work?

* The [Dockerfile](Dockerfile) sets up the pipenv environment, and installs the dependencies
* The [docker-compose.yml](docker-compose.yml) defines the 'app' Docker service and how it should be built
* The [pipeline.yml](.buildkite/pipeline.yml) runs the command using Docker Compose