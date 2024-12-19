# Use Default Linux Universal as base image
FROM mcr.microsoft.com/devcontainers/universal:2-linux

# Install Node.js and npm
RUN apt-get update && \
    apt-get install -y nodejs npm

# Install Vue CLI globally
RUN npm install -g @vue/cli

# Install Flask
RUN pip3 install flask