FROM mcr.microsoft.com/devcontainers/base:ubuntu

# Install required packages
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends \
    make \
    gcc \
    git \
    wget

# Create directory for chain data
RUN mkdir -p /workspace/chain-data

WORKDIR /workspace
