# 🏛️ CompText Ecosystem

> **The Future of LLM Communication** - Token-efficient, structured, production-ready

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Stars](https://img.shields.io/github/stars/ProfRandom92/comptext?style=social)](https://github.com/ProfRandom92/comptext)
[![Discord](https://img.shields.io/badge/Discord-Join%20Us-7289da)](https://discord.gg/comptext)
[![Documentation](https://img.shields.io/badge/docs-latest-blue)](https://github.com/ProfRandom92/comptext-docs)

## 🌐 Architecture Overview

```mermaid
graph TD
    User[👤 User / LLM] -->|Uses| MCP[🚀 MCP Server]
    Developer[👨‍💻 Developer] -->|Integrates| Lib[📦 Python Library]

    MCP -->|Validates via| DSL[📝 DSL Spec]
    Lib -->|Implements| DSL

    MCP -->|Queries| Notion[📚 Notion Codex]
    Developer -->|Reads| Docs[📖 Documentation]

    DSL -->|Defines| Grammar[🧠 Formal Grammar]
    Docs -->|Explains| DSL

    style MCP fill:#4CAF50,stroke:#2E7D32,color:#fff
    style DSL fill:#2196F3,stroke:#1565C0,color:#fff
    style Lib fill:#FF9800,stroke:#E65100,color:#fff
```

## 📊 Ecosystem Status

| Repository | Description | Status | Links |
|------------|-------------|--------|-------|
| **[comptext-mcp-server](https://github.com/ProfRandom92/comptext-mcp-server)** | 🚀 Production MCP Server | ![Build](https://img.shields.io/badge/build-passing-brightgreen) | [Docs](https://github.com/ProfRandom92/comptext-mcp-server#readme) · [Deploy](https://railway.app/new) |
| **[comptext-dsl](https://github.com/ProfRandom92/comptext-dsl)** | 📝 Language Specification | ![Version](https://img.shields.io/badge/version-1.0-blue) | [Grammar](https://github.com/ProfRandom92/comptext-dsl/blob/main/grammar.ebnf) · [Spec](https://github.com/ProfRandom92/comptext-dsl/tree/main/spec) |
| **[comptext-codex](https://github.com/ProfRandom92/comptext-codex)** | 📦 Python Library | ![PyPI](https://img.shields.io/badge/pypi-v1.0-blue) | [Install](https://github.com/ProfRandom92/comptext-codex#installation) · [API](https://github.com/ProfRandom92/comptext-codex/tree/main/docs/api) |
| **[comptext-docs](https://github.com/ProfRandom92/comptext-docs)** | 📚 Documentation Hub | ![Docs](https://img.shields.io/badge/docs-live-success) | [Website](https://profrandom92.github.io/comptext-docs) · [Guides](https://github.com/ProfRandom92/comptext-docs/tree/main/guides) |

## 🎯 Key Features

- **90-95% Token Reduction** - Compress complex operations into minimal syntax
- **Production Ready** - Used in enterprise environments
- **Type-Safe** - Full validation and error handling
- **Extensible** - Plugin architecture for custom commands

## 🚀 Quick Start

```bash
# Install MCP Server
npm install -g @comptext/mcp-server

# Or use Python library
pip install comptext-codex

# Try it now
comptext-cli "fetch(notion, database='projects', limit=10)"
```

## 📖 Learn More

- 📘 [Getting Started Guide](https://github.com/ProfRandom92/comptext-docs/blob/main/getting-started.md)
- 🎓 [Video Tutorials](https://github.com/ProfRandom92/comptext-docs/tree/main/tutorials)
- 💡 [Use Cases](https://github.com/ProfRandom92/comptext-docs/blob/main/use-cases.md)
- 🤝 [Contributing](./CONTRIBUTING.md)

## 🌟 Community

Join our growing community:

- 💬 [Discord Server](https://discord.gg/comptext)
- 🐦 [Twitter/X Updates](https://twitter.com/comptext)
- 📰 [Blog & News](https://github.com/ProfRandom92/comptext-docs/tree/main/blog)

## 📄 License

MIT License - see [LICENSE](./LICENSE) for details.

---

**Built with ❤️ by the CompText Community**
