FROM mcr.microsoft.com/vscode/devcontainers/javascript-node:18-bullseye

# Installing additional OS Packages
RUN apt-get update \
    && apt-get -y install --no-install-recommends \
    curl \
    git-core \
    gnupg \
    locales \
    wget \
    tree \
    jq \
    fontconfig \
    # set up locale
    &&    locale-gen en_US.UTF-8 && fc-cache -vf \ 
    && curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh \
    &&   curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
    
