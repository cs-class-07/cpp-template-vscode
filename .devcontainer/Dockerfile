FROM mcr.microsoft.com/devcontainers/cpp:debian-11

# Section to install additional packages.
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends gcc-10
