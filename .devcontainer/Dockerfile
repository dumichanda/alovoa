# .devcontainer/Dockerfile
FROM mcr.microsoft.com/vscode/devcontainers/base:ubuntu

# install Java & Maven
RUN apt-get update && \
    apt-get install -y openjdk-17-jdk maven git unzip && \
    rm -rf /var/lib/apt/lists/*

# set Java home
ENV JAVA_HOME=/usr/lib/jvm/java-17-openjdk-amd64
