# udacity-kubernetes

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

# prerequisites
    Install docker https://docs.docker.com/install/.
    install kubernetes on docker.
# build images
    Navigate to /udacity-c3-deployment/docker/, open a new terminal
    docker-compose -f docker-compose-build.yaml build --parallel
  # run containers locally
    Navigate to /udacity-c3-deployment/docker/, open a new terminal
    Run the container: docker-compose up
# create cluster
Navigate to /udacity-c3-deployment/k8s, open a new terminal.
Create config maps and secrets.
Create services.
Create pods.

