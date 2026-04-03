FROM mcr.microsoft.com/devcontainers/base:trixie

RUN apt-get update \
    && apt-get install -y --no-install-recommends \
        build-essential \
        dkms \
        mokutil \
        debhelper \
        devscripts \
        dh-exec \
        dh-sequence-dkms \
        lintian \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*
