FROM mcr.microsoft.com/devcontainers/universal:2-linux

RUN apt-get update && \
    apt-get install -y python3 python3-pip && \
    pip install Flask

RUN npm install -g @vue/cli