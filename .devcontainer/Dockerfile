FROM ubuntu:20.04

# Avoid user prompts during package installation
ENV DEBIAN_FRONTEND=noninteractive

# Install essential packages
RUN apt-get update && apt-get install -y \
    curl \
    git \
    vim \
    python3 \
    python3-pip \
    build-essential \
    && apt-get clean

# Set the working directory inside the container
WORKDIR /workspace