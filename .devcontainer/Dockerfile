FROM mcr.microsoft.com/devcontainers/base:ubuntu-22.04
ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt-get install -y \
    build-essential \
    flex \
    bison \
    libfl-dev \
    && rm -rf /var/lib/apt/lists/*
