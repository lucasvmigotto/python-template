# syntax=docker/dockerfile:1

FROM mcr.microsoft.com/devcontainers/python:3.12-bookworm

ARG USERNAME="vscode"

USER ${USERNAME}

WORKDIR /app

RUN curl -LsSf https://astral.sh/uv/install.sh | sh
