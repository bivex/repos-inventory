# 🔌 MCP Servers

> Model Context Protocol (MCP) servers for AI integration

---

## Overview

MCP (Model Context Protocol) is an open protocol that enables AI assistants to securely access external data sources and tools. This category contains 8+ MCP servers built by @bivex.

---

## Featured MCP Servers

### ⭐ [kanboard-mcp](https://github.com/bivex/kanboard-mcp)
- **Language:** Go
- **Stars:** ⭐ 19 | **Forks:** 🍴 7
- **Description:** Complete Kanboard integration with 518 tools
- **Key Features:**
  - Full CRUD operations for projects, tasks, users
  - RBAC support with role-based permissions
  - API key and username/password authentication
  - 46 MCP resources with 100 templates
- **Open Issues:** 1
- **Last Updated:** 2026-02-17
- **[→ Repository](https://github.com/bivex/kanboard-mcp)**

---

### ⭐ [ZenTaoMcp](https://github.com/bivex/ZenTaoMcp)
- **Language:** Go
- **Stars:** ⭐ 2 | **Forks:** 🍴 1
- **Description:** ZenTao 21.7.7 project management integration
- **Key Features:**
  - 518 MCP tools covering all ZenTao modules
  - 46 MCP resources with 100 templates
  - Support for products, projects, stories, tasks, bugs, tests
  - Kanban boards and AI integration (ZAI)
- **Last Updated:** 2026-01-06
- **[→ Repository](https://github.com/bivex/ZenTaoMcp)**

---

### ⭐ [archi-mcp](https://github.com/bivex/archi-mcp)
- **Language:** Python
- **Description:** ArchiMate 3.2 diagram generation with AI
- **Key Features:**
  - Complete ArchiMate 3.2 compliance (55+ element types)
  - All 7 ArchiMate layers supported
  - PlantUML diagram generation
  - 201 comprehensive test cases (59% coverage)
  - Claude Code & Claude Desktop compatible
- **Status:** Production Ready
- **Last Updated:** 2025-12-18
- **[→ Repository](https://github.com/bivex/archi-mcp)**

---

### ⭐ [ILSpy-Mcp](https://github.com/bivex/ILSpy-Mcp)
- **Language:** C#
- **Stars:** ⭐ 3 | **Forks:** 🍴 1
- **Description:** Reverse engineering via ILSpy MCP integration
- **Key Features:**
  - Unlock reverse-engineering productivity
  - ILSpy decompiler integration
  - Production-grade implementation
- **Last Updated:** 2026-02-19
- **[→ Repository](https://github.com/bivex/ILSpy-Mcp)**

---

## Other MCP Servers

### [DiagSession-Mcp](https://github.com/bivex/DiagSession-Mcp)
- **Language:** C#
- **Description:** Analyze Windows ETL trace files from .diagsession archives
- **Key Features:**
  - Clean architecture principles
  - .NET 9 console application
  - Visual Studio-style performance summaries
- **[→ Repository](https://github.com/bivex/DiagSession-Mcp)**

---

### [mcp-logic](https://github.com/bivex/mcp-logic)
- **Language:** Python
- **Description:** Logic calculator utilizing Prover9/Mace4
- **Key Features:**
  - First-order logic theorem proving
  - Python-based MCP server
  - Compatible with Windows Claude App
- **[→ Repository](https://github.com/bivex/mcp-logic)**

---

### [mcp-bpmn](https://github.com/bivex/mcp-bpmn)
- **Language:** TypeScript
- **Description:** BPMN diagram generation via MCP
- **[→ Repository](https://github.com/bivex/mcp-bpmn)**

---

### [binary_ninja_mcp](https://github.com/bivex/binary_ninja_mcp)
- **Language:** Python
- **Description:** Binary Ninja plugin with MCP server
- **Key Features:**
  - Reverse engineering integration
  - Seamless LLM/MCP client connection
- **[→ Repository](https://github.com/bivex/binary_ninja_mcp)**

---

### [MCP-Shared-Memory](https://github.com/bivex/MCP-Shared-Memory)
- **Language:** C#
- **Description:** Shared memory for MCP servers
- **Key Features:**
  - Data sharing between MCP instances
- **[→ Repository](https://github.com/bivex/MCP-Shared-Memory)**

---

## MCP Integrations with Other Projects

### [staruml-controller](https://github.com/bivex/staruml-controller)
- **Language:** JavaScript
- **Description:** StarUML controller for MCP integration
- **Key Features:**
  - Wireframe generation
  - Auto-expand frames
  - Skip dagre for spatial diagrams
- **[→ Repository](https://github.com/bivex/staruml-controller)**

---

### [staruml-controller-bpmn-mcp](https://github.com/bivex/staruml-controller-bpmn-mcp)
- **Language:** HTML
- **Description:** StarUML BPMN controller with MCP
- **[→ Repository](https://github.com/bivex/staruml-controller-bpmn-mcp)**

---

## Summary

| Metric | Count |
|--------|-------|
| **Total MCP Servers** | 8+ |
| **Total Stars** | 24 |
| **Total Forks** | 9 |
| **Languages** | Go, Python, C#, TypeScript, JavaScript |
| **Most Popular** | kanboard-mcp (19⭐) |

---

## Quick Start with MCP Servers

Most MCP servers follow this pattern:
1. Clone the repository
2. Configure environment variables (API keys, endpoints)
3. Build/compile the server
4. Add to Claude Desktop/Claude Code config

Example (kanboard-mcp):
```bash
git clone https://github.com/bivex/kanboard-mcp.git
cd kanboard-mcp
export KANBOARD_API_ENDPOINT="https://your-kanboard/jsonrpc.php"
export KANBOARD_API_KEY="your-api-key"
go build -o kanboard-mcp .
./kanboard-mcp
```

---

**[⬅️ Back to Inventory](../README.md)**
