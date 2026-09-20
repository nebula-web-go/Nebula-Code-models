# NebulaCode

> Custom local AI coding models distributed through Ollama.

[![Ollama](https://img.shields.io/badge/运行%20with-Ollama-8B5CF6?style=for-the-badge&logo=rocket)](https://ollama.com/)
[![Documentation](https://img.shields.io/badge/docs-available-7C3AED?style=for-the-badge)](docs/installation.md)

NebulaCode is a small catalog of custom coding models for local use. Choose a model, copy its command, and let [Ollama](https://ollama.com/) download and run it on your computer.

> **Important:** This repository is documentation and model distribution information only. It does not host or execute the AI models. Ollama handles downloading and running each model locally.

## ✨ Quick start

The basic workflow is simple:

1. [Install Ollama](https://ollama.com/download).
2. Open a terminal.
3. Copy the command for the model you want.
4. Run it.
5. Start chatting with the model.

For example:

```bash
ollama run NebulaCode/nebula-code
```

## Available models

### NebulaCode Nano 0.5B

A very lightweight coding assistant for users who want the smallest NebulaCode option listed here. The `0.5B` parameter size is indicated by the model name.

```bash
ollama run NebulaCode/nebula-code-nano0.5b
```

[Read the Nano model notes →](models/nebula-code-nano.md)

### NebulaCode Lite 3B

A lightweight coding assistant intended for local coding workflows. The `3B` parameter size is indicated by the model name.

```bash
ollama run NebulaCode/nebula-code-lite3b
```

[Read the Lite model notes →](models/nebula-code-lite.md)

### NebulaCode

The main NebulaCode model. Its parameter size has not been specified here.

```bash
ollama run NebulaCode/nebula-code
```

[Read the NebulaCode model notes →](models/nebula-code.md)

## 📊 Model comparison

| Model           |    Size | Intended use                      | Command                                      |
| --------------- | ------: | --------------------------------- | -------------------------------------------- |
| NebulaCode Nano |    0.5B | Very lightweight coding assistant | `ollama run NebulaCode/nebula-code-nano0.5b` |
| NebulaCode Lite |      3B | Lightweight coding assistant      | `ollama run NebulaCode/nebula-code-lite3b`   |
| NebulaCode      | Unknown | Main NebulaCode model             | `ollama run NebulaCode/nebula-code`          |

## Requirements

- [Ollama](https://ollama.com/) installed on your computer.
- A terminal or command prompt.
- An internet connection the first time you run a model so Ollama can download it.

The available system resources and runtime experience depend on your computer and Ollama configuration. This catalog does not define additional hardware requirements.

## Install Ollama

Download Ollama from the official website:

- **All platforms:** [ollama.com/download](https://ollama.com/download)

Follow the installation instructions for your operating system. After installation, open a new terminal and verify that Ollama is available:

```bash
ollama --version
```

For more installation guidance, see [docs/installation.md](docs/installation.md).

## Run a model

Run any listed model with its exact command:

```bash
# Very lightweight option
ollama run NebulaCode/nebula-code-nano0.5b

# Lightweight option
ollama run NebulaCode/nebula-code-lite3b

# Main NebulaCode model
ollama run NebulaCode/nebula-code
```

Ollama downloads the selected model if needed and opens an interactive chat in your terminal. Type a prompt and press **Enter** to send it.

### Basic usage

Once a model is running, you can ask it coding questions in natural language. For useful results, include relevant context such as:

- The language or framework you are using.
- The goal or expected behavior.
- Error messages and relevant code.
- Constraints such as runtime, style, or compatibility requirements.

Use `Ctrl+D` or `Ctrl+C` to leave the interactive session, depending on your terminal and operating system.

## FAQ

### Does this repository run the models?

No. This repository is a public catalog and documentation project. The models run locally through Ollama on your computer.

### Where are the model files hosted?

The model references are available through Ollama. When you run a command, Ollama handles downloading and running the selected model.

### Do I need Ollama installed?

Yes. Install Ollama before using any command in this repository.

### Which model should I try first?

Try **NebulaCode Nano** for the very lightweight option, **NebulaCode Lite** for a lightweight coding assistant, or **NebulaCode** for the main model. You can try more than one and choose the one that fits your workflow.

### Are these models cloud-hosted?

The commands in this repository are intended to run the models locally through Ollama. Ollama manages the local runtime after the model is downloaded.

### Is the parameter size of every model listed?

No. The sizes `0.5B` and `3B` are part of the Nano and Lite model names. The parameter size of the main NebulaCode model has not been specified.

## Troubleshooting

### `ollama: command not found`

Ollama is either not installed or is not available in your terminal's `PATH`. Install Ollama from [ollama.com/download](https://ollama.com/download), then open a new terminal and try again.

### The model does not start

Check that you copied the command exactly, including capitalization and punctuation. Confirm that Ollama is installed and available by running:

```bash
ollama --version
```

Then retry the model command.

### The first run takes time

The first run may take longer because Ollama needs to download the model. After the download completes, try the command again if necessary.

### I need more help with Ollama

For Ollama-specific installation and runtime help, consult the [official Ollama documentation](https://docs.ollama.com/) and [Ollama repository](https://github.com/ollama/ollama).

## Contributing

Contributions that improve clarity, correct documentation errors, or make the model catalog easier to use are welcome. Before opening a pull request:

1. Keep the repository documentation-only.
2. Preserve the exact Ollama commands listed above.
3. Do not add unverified model specifications.
4. Explain what the change improves for users.

## License

No license has been selected for this repository yet. Until a license is added, the contents remain subject to the repository owner's rights under applicable law. Please open an issue before reusing or redistributing repository content beyond what GitHub's interface permits.

## Repository map

```text
├── README.md
├── models/
│   ├── nebula-code-nano.md
│   ├── nebula-code-lite.md
│   └── nebula-code.md
└── docs/
    └── installation.md
```
