# 🤖 AI/LLM Tools

> Tools for AI development, coding agents, and LLM orchestration

---

## Featured Projects

### [ultra-builder-pro](https://github.com/bivex/ultra-builder-pro)
- **Language:** Python
- **Version:** 4.4.0
- **Status:** Production Ready
- **Description:** Production-Grade AI-Powered Development System for Claude Code
- **Core Philosophy - Priority Stack (CLAUDE.md):**
  1. Role + Safety — Deployable code, KISS/YAGNI, think in English
  2. Context Blocks — Honor XML blocks exactly as written
  3. Evidence-First — External facts require verification (Context7/Exa MCP)
  4. Honesty & Challenge — Challenge user assumptions, name logical gaps
  5. Architecture — Critical state must be persistable/recoverable/observable
  6. Code Quality — No TODO/FIXME/placeholder, modular, avoid deep nesting
  7. Testing — No mocking core logic, external deps allow test doubles
  8. Action Bias — Default to progress, high-risk must brake and ask
- **Production Absolutism:**
  > "There is no test code. There is no demo. There is no MVP. Every line is production code."
  ```
  Code Quality = Real Implementation × Real Tests × Real Dependencies
  If ANY component is fake/mocked/simulated → Quality = 0
  ```
- **Features:**
  - 8 commands
  - 6 skills
  - Claude Code config integration
- **Installation:**
  ```bash
  git clone https://github.com/bivex/ultra-builder-pro.git
  cd ultra-builder-pro
  cp -r ./* ~/.claude/
  claude
  ```
- **[→ Repository](https://github.com/bivex/ultra-builder-pro)**

---

### [codex](https://github.com/bivex/codex)
- **Language:** Rust
- **Source:** OpenAI
- **Description:** Codex CLI is a coding agent from OpenAI that runs locally on your computer
- **Key Features:**
  - Local execution (no cloud dependency)
  - IDE integration (VS Code, Cursor, Windsurf)
  - Cloud-based option available (Codex Web)
- **Installation:**
  ```bash
  # npm
  npm install -g @openai/codex

  # Homebrew
  brew install --cask codex

  # Run
  codex
  ```
- **[→ Repository](https://github.com/bivex/codex)**

---

### [opencode](https://github.com/bivex/opencode)
- **Language:** TypeScript
- **Website:** https://opencode.ai
- **Description:** The open source AI coding agent
- **Key Features:**
  - Desktop application (BETA)
  - Terminal UI
  - Discord community integration
  - NPM package: `opencode-ai`
  - Cross-platform support (macOS, Windows, Linux)
- **Installation:**
  ```bash
  # Quick install
  curl -fsSL https://opencode.ai/install | bash

  # npm
  npm i -g opencode-ai@latest

  # Homebrew
  brew install opencode

  # Chocolatey (Windows)
  choco install opencode

  # Scoop (Windows)
  scoop install extras/opencode
  ```
- **Desktop App Platforms:**
  - macOS (Apple Silicon & Intel)
  - Windows
  - Linux (.deb, .rpm, AppImage)
- **[→ Repository](https://github.com/bivex/opencode)**

---

### [codex-openai-proxy](https://github.com/bivex/codex-openai-proxy)
- **Language:** Go
- **Description:** Proxy server to use ChatGPT Plus tokens with CLINE/Claude Code extensions via OpenAI API compatibility
- **[→ Repository](https://github.com/bivex/codex-openai-proxy)**

---

### [NubemGenesisMCP](https://github.com/bivex/NubemGenesisMCP)
- **Language:** Python
- **Description:** NubemGenesis-MCP: Advanced Meta-MCP AI System with 141 Personas - Production Deployment
- **Key Features:**
  - 141 AI personas
  - Meta-MCP architecture
  - Production ready
- **[→ Repository](https://github.com/bivex/NubemGenesisMCP)**

---

### [test_mcp_wireframe_groq](https://github.com/bivex/test_mcp_wireframe_groq)
- **Language:** Python 3.x (macOS with Homebrew)
- **Description:** Run Claude Code using free Groq models instead of the Anthropic API
- **Requirements:**
  - macOS with Python 3.x
  - [Claude Code](https://github.com/anthropics/claude-code) installed
  - Groq API key: https://console.groq.com
- **Architecture:**
  ```
  Claude Code
      │  POST /v1/messages (tools: 200 items)
      ▼
  middleware.py :4000
      │  trims tools to 128
      ▼
  LiteLLM :4001
      │  maps claude-sonnet-4-6 → groq/openai/gpt-oss-120b
      ▼
  Groq API
  ```
- **Key Features:**
  - LiteLLM proxy setup
  - Middleware trims tools list from 200+ to 128 (Groq limit)
  - Maps Claude model names to Groq models
  - uvloop fix for Python 3.14 incompatibility
- **Available Groq Models:**
  - `openai/gpt-oss-120b` — GPT-OSS 120B (recommended)
  - `openai/gpt-oss-20b` — GPT-OSS 20B (faster)
  - `llama-3.3-70b-versatile` — Llama 3.3 70B
  - `moonshotai/kimi-k2-instruct` — Kimi K2
- **[→ Repository](https://github.com/bivex/test_mcp_wireframe_groq)**

---

### [qdrant_streamlit_generator_via_groq](https://github.com/bivex/qdrant_streamlit_generator_via_groq)
- **Language:** Python
- **Description:** Qdrant Psychological Scenarios System
- **[→ Repository](https://github.com/bivex/qdrant_streamlit_generator_via_groq)**

---

### [pl-claude](https://github.com/bivex/pl-claude)
- **Description:** A Claude Code project for coordinating projects using Zettelkasten method in Obsidian-compatible Markdown files
- **[→ Repository](https://github.com/bivex/pl-claude)**

---

### [hu-claude](https://github.com/bivex/hu-claude)
- **Language:** Python
- **Description:** AI for self improvement
- **[→ Repository](https://github.com/bivex/hu-claude)**

---

## Summary

| Metric | Count |
|--------|-------|
| **Total AI Tools** | 9+ |
| **Languages** | Python, Rust, TypeScript, Go |
| **Key Focus** | Coding agents, MCP integration, Groq API |
| **Production Ready** | 4+ (ultra-builder-pro, codex, opencode, test_mcp_wireframe_groq) |

---

**[⬅️ Back to Inventory](../README.md)**
