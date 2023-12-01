FROM mcr.microsoft.com/devcontainers/base:jammy

VOLUME [ "/home/vscode", "/home/vscode/.vscode-server", "/src" ]

USER root

RUN mkdir -p /src && chown -R vscode:vscode /src && \
    mkdir -p /home/vscode && chown -R vscode:vscode /home/vscode && \
    mkdir -p /home/vscode/.vscode-server && chown -R vscode:vscode /home/vscode/.vscode-server
