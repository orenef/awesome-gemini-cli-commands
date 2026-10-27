# Awesome Gemini CLI Custom Commands [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> ✨ A curated collection of **Gemini CLI custom commands** that extend Gemini into agent-like modes, similar to GitHub Copilot agents.  
> Each command is defined as a simple `.toml` file you can install and start using right away.

---

## 📖 Contents
- [Introduction](#introduction)
- [Available Commands](#available-commands)
  - [Security](#security)
  - [Developer Productivity](#developer-productivity)
  - [Knowledge Sharing](#knowledge-sharing)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

---

## 🌟 Introduction
Gemini CLI supports **custom commands**, allowing you to define prompts that act like specialized agents.  
This repository collects useful commands across **security, productivity, and developer tools** to help you get started.

Each command is defined in a `.toml` file under the [`commands/`](./commands) directory.

---

## 🛠 Available Commands

### 🔐 Security
- **[Threat Model Generator](./commands/threat-model-generator.toml)** – Creates a STRIDE-style threat model from a system description.  
- **[Dependency Risk Analyzer](./commands/dependency-risk-analyzer.toml)** – Reviews dependency lists for risks and vulnerabilities.  
- **[License Checker](./commands/license-checker.toml)** – Analyzes dependencies’ licenses and highlights risks.  

### ⚙️ Developer Productivity
- **[Regex Explainer](./commands/regex-explainer.toml)** – Explains complex regular expressions in plain language.  
- **[APN Contract Inspector](./commands/apn-contract.toml)** – Inspects an existing Agent Payment Node CLI discovery contract on Apple Silicon macOS; reports prerequisites and advertised capabilities without payment operations.

### 📑 Knowledge Sharing
- **[Knowledge Sharing](./commands/knowledge-sharing.toml)** – Transforms notes into a shareable technical doc.  
- **[Presenter Maker (Slidev)](./commands/presenter-maker-slidev.toml)** – Generates Slidev presentation outlines from a 

🤝 Contributing

Contributions are welcome! 🎉

To add a new command:

Create a new .toml file

Follow the existing format (description + prompt).

Add your command to the Available Commands section in this README.

Open a pull request.