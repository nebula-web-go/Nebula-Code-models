<img width="1380" height="708" alt="image" src="https://github.com/user-attachments/assets/bef99e32-5ce4-413c-86f8-9aad7da68c52" />

NebulaCode is a family of local coding models for Ollama. This repository is a simple catalog: choose a model, copy the command, and run it on your machine.

A clean way to discover the official NebulaCode model commands without adding extra tooling or app layers.

## 🚀 Quick Start

1. Install Ollama.
2. Open a terminal.
3. Pick a model from the list below.
4. Copy the exact command.
5. Run it with Ollama.

Example:

```bash
ollama run NebulaCode/nebula-code
```

## 🧠 Models

### NebulaCode Nano

A very small local option for people who want the lightest model in the family.

> Best for: users who want the smallest and simplest option.

```bash
ollama run NebulaCode/nebula-code-nano0.5b
```

### NebulaCode Lite

A lightweight NebulaCode option designed for local use with a balanced footprint.

> Best for: users who want an intermediate local choice.

```bash
ollama run NebulaCode/nebula-code-lite3b
```

### NebulaCode

The main NebulaCode model.

> Best for: users who want the primary model in the family.

```bash
ollama run NebulaCode/nebula-code
```

## 📊 Model Commands

| Model | Size | Command |
| --- | --- | --- |
| NebulaCode Nano | 0.5B | `ollama run NebulaCode/nebula-code-nano0.5b` |
| NebulaCode Lite | 3B | `ollama run NebulaCode/nebula-code-lite3b` |
| NebulaCode | Not specified | `ollama run NebulaCode/nebula-code` |

## 📦 Requirements

- Ollama installed on your computer.
- Internet access for the initial model download.
- Hardware capable of running the selected model.

## ⚡ Installation

Install Ollama from the official site:

- [Ollama download](https://ollama.com/download)

After installation, verify it is available:

```bash
ollama --version
```

## 💻 Usage

Run any model with its exact command:

```bash
ollama run NebulaCode/nebula-code-nano0.5b
```

```bash
ollama run NebulaCode/nebula-code-lite3b
```

```bash
ollama run NebulaCode/nebula-code
```

Once the model is running, you can start a local conversation in the terminal with Ollama.

## ❓ FAQ

### Do I need an API key?

No. These commands are intended to run locally through Ollama.

### Does this run on my computer?

Yes. Ollama downloads and runs the model locally on your machine.

### Is this repository an application?

No. This repository is a model catalog and documentation hub.

### Can I use these models without Ollama?

The instructions in this repository use Ollama as the official runtime for execution.

## 🛠 Troubleshooting

### `ollama` is not recognized

Make sure Ollama is installed and available in your terminal `PATH`.

### The model is taking time to download

The first run needs to download the model. This depends on your internet connection and the selected model.

### The model does not start

Check that Ollama is running correctly, then verify the installation with:

```bash
ollama list
```

## 📁 Repository Structure

```text
Nebula-Code-models/
├── README.md
├── models/
│   ├── nebula-code-nano.md
│   ├── nebula-code-lite.md
│   └── nebula-code.md
└── docs/
    └── installation.md
```

## 🤝 Contributing

Contributions to improve clarity, fix documentation mistakes, or make the model catalog easier to use are welcome. Open an issue or pull request with a clear explanation of the change.

## 📄 License

No license has been selected for this repository yet. Please check the repository status before reusing the contents beyond personal reference.

---

NebulaCode is a simple, local-first model catalog for Ollama. Pick a model, run the command, and start using it.
