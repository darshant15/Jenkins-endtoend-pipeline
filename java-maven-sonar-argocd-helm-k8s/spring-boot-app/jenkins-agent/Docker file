FROM maven:3.9.9-eclipse-temurin-17

RUN apt-get update && \
    apt-get install -y git curl

RUN curl -fsSL https://get.docker.com | sh

WORKDIR /workspace
