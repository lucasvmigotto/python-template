# .python-template

[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white)](https://conventionalcommits.org)

## Development

### Pre-requisites

* [Docker CE](https://docs.docker.com/engine/install/ubuntu/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Dev Container](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

### Docker

#### Useful commands

* Open a terminal session inside Dev Container

    ```bash
    docker exec -it $(docker ps -qaf "name=vsc-python-template") bash
    ```

## References

* Dependencies
  * [uv](https://docs.astral.sh/uv/)
* Docker
  * [Docs](https://docs.docker.com/get-started/)
  * [Dev Container](https://code.visualstudio.com/docs/devcontainers/create-dev-container)
* Visual Studio Code
  * [Python: Settings](https://code.visualstudio.com/docs/python/settings-reference)
* Miscellaneous
  * [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
