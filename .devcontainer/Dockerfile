FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:20-bullseye

#FROM mcr.microsoft.com/devcontainers/base:ubuntu-24.04

# Install Node.js (LTS), pnpm, npx, and git in one layer, clean up after
RUN export DEBIAN_FRONTEND=noninteractive \
    && apt-get update \
    && apt-get install -y npm nodejs git \
    && npm install -g pnpm npx \
    && apt-get install -y python3 build-essential \
    && rm -rf /var/lib/apt/lists/*

# Install zsh
RUN apt-get update && apt-get install -y zsh && rm -rf /var/lib/apt/lists/*

# Install chezmoi for dotfiles management
#RUN sh -c "$(curl -fsLS get.chezmoi.io)" -- -b /usr/local/bin

# (chezmoi initialization moved to postCreateCommand in devcontainer.json; no need to do it here)

# Set working directory
WORKDIR /workspace
