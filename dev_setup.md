# Canonical development environment setup

1. install VS Code: <https://code.visualstudio.com/>
    1. install "Remote Development" and "Remote - Containers" extensions
1. install Docker (Desktop): <https://www.docker.com/get-started>
    1. `docker pull python:3.9.1-buster`
1. create folder e.g. biostat821/, open folder in VS Code
1. create .devcontainer.json:

    ```json
    {
        "image": "python:3.9.1-buster"
    }
    ```

1. if you want to access GitHub via SSH from the Dev Container: <https://code.visualstudio.com/docs/remote/containers#_using-ssh-keys>
1. open command palette: CTRL-SHIFT-P (CMD-SHIFT-P on Mac)
    1. run "Remote Containers: Reopen in Container"
1. open integrated terminal: CTRL-` (backtick)
    1. `python --version`
1. install "Live Share" VS Code extension _in Dev Container_
