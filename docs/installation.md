# Installing Ollama

NebulaCode models are designed to run locally through Ollama. Install Ollama before using any command in this repository.

## 1. Download Ollama

Use the official installer:

- [Download Ollama](https://ollama.com/download)

Choose the version for your operating system and follow the setup steps.

## 2. Verify the installation

Open a new terminal and run:

```bash
ollama --version
```

If the command is not found, restart the terminal or confirm that Ollama was installed correctly.

## 3. Run a NebulaCode model

Choose one of these exact commands:

```bash
ollama run NebulaCode/nebula-code-nano0.5b
```

```bash
ollama run NebulaCode/nebula-code-lite3b
```

```bash
ollama run NebulaCode/nebula-code
```

On the first run, Ollama may download the selected model. Once it starts, you can begin chatting with it in the terminal.

## 4. What this repository is

This repository is a catalog and documentation hub for NebulaCode models. It does not host or execute the models itself, and it does not provide a frontend, backend, API, database, or application layer.
