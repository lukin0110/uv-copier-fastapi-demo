[![Lint and Test](https://github.com/lukin0110/poetry-copier-fastapi-demo/actions/workflows/test.yml/badge.svg)](https://github.com/lukin0110/poetry-copier-fastapi-demo/actions)

# Marty McFly

An example of a FastAPI app that was scaffolded with Poetry Copier.

## 🚀 Using

*Prerequisite*: the following command needs to be executed inside a DevContainer. See [Contributing section](#-contributing) to get started.

To serve this app, run:
```bash
poe serve --dev
```
and open [localhost:8000](https://localhost:8000) in your browser.


## 🧑‍💻 Contributing

<details>
<summary>Prerequisites</summary>

<details>
<summary>1. Install Docker</summary>

1. Go to [Docker](https://www.docker.com/get-started), download and install docker.
2. [Configure Docker to use the BuildKit build system](https://docs.docker.com/build/buildkit/#getting-started). On macOS and Windows, BuildKit is enabled by default in Docker Desktop.

</details>

<details>
<summary>2. Install VS Code</summary>

Go to [VS Code](https://code.visualstudio.com/), download and install VS Code.
</details>

</details>

#### 1. Open DevContainer with VS Code
Open this repository with VS Code, and run <kbd>Ctrl/⌘</kbd> + <kbd>⇧</kbd> + <kbd>P</kbd> → _Dev Containers: Reopen in Container_.

The following commands can be used inside a DevContainer.

#### 2. Run linters
```bash
poe lint
```

#### 3. Run tests
```bash
poe test
```

#### 4. Update uv lock file
```bash
uv lock
```

---
See how to develop with [PyCharm or any other IDE](https://github.com/lukin0110/uv-copier/tree/main/docs/ide.md).

---
️⚡️ Scaffolded with [Uv Copier](https://github.com/lukin0110/uv-copier/).\
🛠️ [Open an issue](https://github.com/lukin0110/uv-copier/issues/new) if you have any questions or suggestions.
