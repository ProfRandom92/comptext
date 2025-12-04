# 🌍 CompText Ecosystem

**Token-Efficient Communication for LLMs**

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![MCP Server](https://img.shields.io/badge/MCP-Ready-green)](https://github.com/ProfRandom92/comptext-mcp-server)
[![DSL](https://img.shields.io/badge/DSL-v1.0-orange)](https://github.com/ProfRandom92/comptext-dsl)
[![Docs](https://img.shields.io/badge/Docs-Complete-brightgreen)](https://github.com/ProfRandom92/comptext-docs)

---

## 🎯 What is CompText?

CompText is a complete open-source ecosystem for **reducing LLM token usage by 90-95%** through domain-specific language patterns.

Instead of:
```
"Here's my entire project setup... [25,000 tokens]"
```

Use:
```
use:project-setup-v2  [50 tokens]
```

**Result:** 99.8% reduction!

---

## 📦 Components

### 1️⃣ [CompText DSL](https://github.com/ProfRandom92/comptext-dsl)
**Domain-Specific Language for LLM communication**

- Structured, versioned commands
- 90-95% token reduction
- Git-friendly
- Team standardization

### 2️⃣ [MCP Server](https://github.com/ProfRandom92/comptext-mcp-server)
**Universal integration layer**

- Native MCP Protocol
- REST API
- Works with: Claude, Perplexity, Cursor, ChatGPT, LM Studio
- Production-ready: Docker, CI/CD, tests

### 3️⃣ [Public Codex](https://notion.so/0d571dc857144b199243ea951d60cef6)
**150+ ready-to-use commands**

- Development patterns
- DevOps workflows
- Documentation templates
- Open for contributions

### 4️⃣ [Documentation](https://github.com/ProfRandom92/comptext-docs)
**Complete guides and tutorials**

- Getting started
- Language reference
- Integration guides
- API documentation

---

## 🚀 Quick Start

### Install MCP Server

```bash
git clone https://github.com/ProfRandom92/comptext-mcp-server.git
cd comptext-mcp-server
bash setup.sh
```

### Configure Your Platform

**Claude Desktop:**
```json
{
  "mcpServers": {
    "comptext": {
      "command": "python",
      "args": ["-m", "comptext_mcp"]
    }
  }
}
```

**Others:** See [Platform Guides](https://github.com/ProfRandom92/comptext-docs)

---

## ✨ Key Features

🌐 **Universal Compatibility**
- Claude Desktop
- Cursor AI  
- Perplexity
- ChatGPT
- LM Studio
- Jan.ai
- Ollama

🔧 **Production Ready**
- Docker deployment
- CI/CD pipelines
- Comprehensive tests
- Full documentation

📚 **Open Source**
- MIT License
- Community driven
- Contributions welcome

---

## 📈 Benefits

### For Developers
- 💰 **Reduce API costs** by 90-95%
- ⚡ **Faster responses** - less data to process
- 📝 **Version control** your prompts
- 👥 **Team standardization**

### For Teams
- 🛠️ **Shared knowledge base**
- 📖 **Consistent practices**
- 🔄 **Easy updates** via Notion
- 📄 **Documentation as code**

### For AI Researchers
- 🧪 **Reproducible experiments**
- 📊 **Efficient benchmarking**
- 🔍 **Structured prompts**
- 💾 **Shareable datasets**

---

## 📚 Documentation

- [Getting Started](https://github.com/ProfRandom92/comptext-docs/blob/main/getting-started/README.md)
- [Language Guide](https://github.com/ProfRandom92/comptext-docs/blob/main/language-guide/README.md)
- [MCP Integration](https://github.com/ProfRandom92/comptext-docs/blob/main/mcp-integration/README.md)
- [API Reference](https://github.com/ProfRandom92/comptext-docs/blob/main/api-reference/README.md)
- [Examples](https://github.com/ProfRandom92/comptext-docs/blob/main/examples/README.md)

---

## 🔗 Links

- **MCP Server:** [comptext-mcp-server](https://github.com/ProfRandom92/comptext-mcp-server)
- **DSL Spec:** [comptext-dsl](https://github.com/ProfRandom92/comptext-dsl)
- **Documentation:** [comptext-docs](https://github.com/ProfRandom92/comptext-docs)
- **Public Codex:** [Notion](https://notion.so/0d571dc857144b199243ea951d60cef6)

---

## 🤝 Contributing

We welcome contributions! See [CONTRIBUTING.md](CONTRIBUTING.md)

---

## 📝 License

**MIT License** - Free for commercial and personal use.

---

**Built with ❤️ for the AI/LLM developer community**
