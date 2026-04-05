FROM mcr.microsoft.com/devcontainers/base:trixie
RUN apt-get update && \
    apt-get -y --no-install-recommends install pipx && \
    rm -rf /var/lib/apt/lists/*
RUN pipx ensurepath && \ 
    pipx install --include-deps ansible-dev-tools==26.3.1