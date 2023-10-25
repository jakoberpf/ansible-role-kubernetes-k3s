FROM mcr.microsoft.com/devcontainers/base:bullseye
# Install pyhton's package manager and virtual environment
RUN apt-get update && apt-get install -y python3-venv python3-pip
# Install the ansible and molecule packages
RUN pip install molecule molecule[docker]
