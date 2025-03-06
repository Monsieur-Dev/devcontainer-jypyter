# Jupyter Dev Container

This repository is a simple vscode dev container that can pops a Juniper instance in just a few clics.

## How to use this

1. Install prerequisites: WSL2 (for Windows users), DockerDesktop, and vscode.
2. Clone the repository.
3. Open the folder using vscode **in container mode**.
4. Open the `Notebook.ipynb` to see an example.

> The Jupyter server url is **`http://localhost:8888`**.

> The password for the server is **`password`** (can be changed it in the `.devcontainer/.env` file, you'll need to rebuild the container for the changes to take effect).
