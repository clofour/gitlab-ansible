FROM mcr.microsoft.com/devcontainers/base:trixie
RUN apt-get update && \
    apt-get -y --no-install-recommends install pipx && \
    pipx ensurepath
RUN pipx install --include-deps ansible-dev-tools==26.3.1