FROM python:3.14.0a1-slim

# Install common utilities
RUN apt-get update && apt-get install -y \
    build-essential \
    curl \
    wget \
    software-properties-common

# Clean up
RUN apt-get clean && rm -rf /var/lib/apt/lists/*

# Set the working directory
WORKDIR /workspace
