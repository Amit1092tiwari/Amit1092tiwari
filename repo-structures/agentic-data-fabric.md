# 📦 Repository: agentic-data-fabric

> **Visibility:** 🌐 Public | **Default Branch:** `main` | **Size:** 0.05 MB | **License:** `Apache-2.0` | **Maturity:** 🏆 **Grade A+ (98%)**

- **GitHub Remote:** [https://github.com/Amit1092tiwari/agentic-data-fabric](https://github.com/Amit1092tiwari/agentic-data-fabric)
- **Primary Domain:** Enterprise Deterministic Data Fabric & Autonomous Model Context Protocol (MCP) Lakehouse Governor
- **Antigravity Route:** `~/.gemini/config/mcp_config.json` $\rightarrow$ `agentic-data-fabric`

---

## 📝 Description
Production-grade deterministic semantic and execution fabric enabling autonomous AI agents (Claude, Gemini, Antigravity, Cursor) to discover, inspect, query, and govern Lakehouse assets via the Model Context Protocol (MCP) with an integrated self-healing compaction governor.

---

## 🛠️ File Extensions & Content Distribution

| File Type | Purpose |
| :--- | :--- |
| `.py` | Core engine, AST guardrails, MCP server, and governor loops |
| `.yml` | GitHub Actions CI automation |
| `.md` | Architectural documentation, changelog, and guidelines |
| `.txt` | Python dependency contracts |

---

## ⚡ CI/CD Automation & Workflows
- ⚡ `ci.yml`: Automated pytest execution, AST guardrail assertion, and compaction checksum validation.

---

## 📂 Directory & File Hierarchy

```text
agentic-data-fabric/
├── .github/
│   └── workflows/
│       └── ci.yml
├── .gitignore
├── CHANGELOG.md
├── LICENSE
├── README.md
├── requirements.txt
├── src/
│   ├── fabric/
│   │   ├── engine.py
│   │   └── guardrails.py
│   ├── governor/
│   │   ├── compactor.py
│   │   └── watcher.py
│   └── mcp_server/
│       └── server.py
└── tests/
    └── test_fabric.py
```
