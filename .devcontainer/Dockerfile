ARG VARIANT=ubuntu-22.04
FROM mcr.microsoft.com/vscode/devcontainers/base:0-${VARIANT}

RUN apt update \
    && apt install -y gcc make binutils libc6-dev gdb

# Add optional library for develop.
RUN apt install -y bash-completion