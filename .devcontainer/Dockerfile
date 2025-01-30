# FROM python:3.13-bookworm
FROM ubuntu:24.10

RUN apt update && apt install -y --no-install-recommends \
    fish \
    git \
    openssh-client \
    python3 \
    python3-pip \
    python3-venv \
    && rm -rf /var/lib/apt/lists/*
