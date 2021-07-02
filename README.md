- [About](#about)
- [Variables](#variables)
- [Deployment](#deployment)

# About

This project builds Docker images from Dockerfiles and pushes them to the GitLab container registry.

# Variables

| Variable        | Description                                    | Default    | Optional/Required |
|-----------------|------------------------------------------------|------------|-------------------|
| DIRECTORY       | The directory in which the Dockerfile is saved |            | Required          |
| IMAGE_NAME      | Image name for the to be created Docker image  |            | Required          |
| IMAGE_TAG       | Tag for the to be created Docker image         |            | Required          |
| DOCKERFILE_NAME | File name for the Dockerfile                   | Dockerfile | Required          |

# Deployment
Manual deployment only (through the GitLab web console)