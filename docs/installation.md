# Installing Ollama

NebulaCode models run locally through [Ollama](https://ollama.com/). Ollama must be installed before you run any model command in this repository.

## 1. Download Ollama

Use the official download page:

[Download Ollama](https://ollama.com/download)

Choose the installer for your operating system and follow the on-screen instructions.

## 2. Verify the installation

Open a new terminal and run:

```bash
ollama --version
```

If your terminal reports that `ollama` cannot be found, restart the terminal after installation. If the command is still unavailable, consult the [official Ollama documentation](https://docs.ollama.com/).

## 3. Run NebulaCode

Choose one of the exact commands below:

```bash
ollama run NebulaCode/nebula-code-nano0.5b
```

```bash
ollama run NebulaCode/nebula-code-lite3b
```

```bash
ollama run NebulaCode/nebula-code
```

On the first run, Ollama may need to download the selected model. Once it starts, type your prompt in the terminal and press **Enter**.

## What this repository does

This repository provides documentation and copy-friendly model commands. It does not host or execute the AI models, and it does not provide an application, API, database, or model management interface. Ollama handles the local download and runtime.
