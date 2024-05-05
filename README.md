# Universal Image Dev Container Configuration with GitHub Extensions

This repository contains a baseline configuration for a development container using the [Default Universal Linux template](https://github.com/devcontainers/templates/tree/main/src/universal). The Dev Container is pre-configured with several Visual Studio Code extensions from GitHub to ease the experience when working with GitHub services.

## Dev Container

The development container is defined in the [devcontainer.json](.devcontainer/devcontainer.json) file. It uses the `mcr.microsoft.com/devcontainers/universal:2-linux` image and includes several customizations for Visual Studio Code.

## GitHub Extensions

The following GitHub extensions are pre-installed in the dev container:

- [GitHub Actions](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-github-actions)
- [GitHub CodeQL](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-codeql)
- [GitHub Codespaces](https://marketplace.visualstudio.com/items?itemName=GitHub.codespaces)
- [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
- [GitHub Pull Request](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)
- [GitHub Repositories](https://marketplace.visualstudio.com/items?itemName=GitHub.remotehub)

These extensions are specified in the `customizations.vscode.extensions` field in the [devcontainer.json](.devcontainer/devcontainer.json) file.

## Dependabot

This repository also includes a [Dependabot configuration](.github/dependabot.yml) that [checks for updates to dev container features](https://docs.github.com/en/code-security/dependabot/dependabot-version-updates/configuration-options-for-the-dependabot.yml-file#dev-containers) on a weekly basis.

At time of writing, the dev container template in this repository does not list any features.

## Getting Started

Use this repository as a basis to bootstrap a repository with a pre-configured development container and GitHub extensions. To get started, click the "Use this template" button at the top of the repository.

This allows you get started quickly with GitHub Codespaces.

## Additional information

- [GitHub Codespaces Overview](https://docs.github.com/en/codespaces/overview)
- [GitHub Codespaces Docs: Tips for making your allowed usage go further](https://docs.github.com/en/codespaces/troubleshooting/troubleshooting-included-usage#tips-for-making-your-allowed-usage-go-further)