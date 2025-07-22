FROM mcr.microsoft.com/devcontainers/base:ubuntu-24.04

# Install Node.js (LTS), pnpm, npx, and git in one layer, clean up after
RUN export DEBIAN_FRONTEND=noninteractive \
    && curl -fsSL https://deb.nodesource.com/setup_lts.x | bash - \
    && apt-get update \
    && apt-get install -y nodejs git \
    && npm install -g pnpm npx \
    && rm -rf /var/lib/apt/lists/*

# Set working directory
WORKDIR /workspace
