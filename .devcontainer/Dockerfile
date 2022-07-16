# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.222.0/containers/python-3/.devcontainer/base.Dockerfile

ARG VARIANT="16-bullseye"
ARG TERRAFORM_VERSION="1.1.0"
FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:${VARIANT}

# Install Trivy
RUN curl -sfL https://raw.githubusercontent.com/aquasecurity/trivy/main/contrib/install.sh | sh -s -- -b /usr/local/bin v0.24.1

# Install Skaffold
RUN curl -Lo skaffold https://storage.googleapis.com/skaffold/releases/latest/skaffold-linux-amd64 && \
    sudo install skaffold /usr/local/bin/ && \
    rm ./skaffold
