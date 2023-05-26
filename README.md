Appsilon Infrastructure Engineer Task - Part 1: Containers + CI/CD



Task: Build a container image, and push it into a registry

Scenario: You have a simple Python application written with Flask. You need to build a container image so that it can be deployed somewhere later on.

To Do:
1) Create a Hello World Python Flask application with an endpoint (you can copy-paste example code from Flask documentation)
2) Prepare the Dockerfile, which can be used to build the container. Provide information how to build the image locally (with Docker/Podman) and run the container
3) Prepare CI process (GitHub Workflows/Gitlab CI), which builds the container image, and pushes it to a registry (e.g. Docker Hub, Quay.io, GitHub Container Registry). The CI should be run on push to main branch, and periodically on Saturday at 7 PM (push an image with the latest tag)

Docker Hub repository: https://hub.docker.com/repository/docker/dv6102work/app.py/general
