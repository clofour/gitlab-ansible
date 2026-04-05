FROM mcr.microsoft.com/devcontainers/base:trixie
RUN apt-get update && \
    apt-get -y --no-install-recommends install pipx && \
    pipx ensurepath
RUN useradd -m -s /bin/bash dev
USER dev
RUN pipx install --include-deps ansible-dev-tools==26.3.1