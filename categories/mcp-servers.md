# 🔌 MCP Servers

> Model Context Protocol (MCP) servers for AI integration with external systems

---

## Overview

MCP (Model Context Protocol) is an open protocol that enables AI assistants to securely access external data sources and tools. This category contains 9+ MCP servers built by @bivex with varying levels of maturity and features.

---

## Featured MCP Servers

### ⭐ [kanboard-mcp](https://github.com/bivex/kanboard-mcp)
- **Language:** Go 1.21+
- **Stars:** ⭐ 19 | **Forks:** 🍴 7
- **License:** MIT
- **Description:** Powerful Go-based MCP server that enables seamless integration between AI assistants (like Claude Desktop, Cursor) and Kanboard project management system
- **Key Features:**
  - 🔗 Seamless Kanboard Integration — Direct API communication
  - 🤖 Natural Language Processing — Use plain English to manage projects
  - 📊 Complete Project Management — Handle projects, tasks, users, columns
  - 🔐 Secure Authentication — API key and username/password auth support
  - ⚡ High Performance — Built with Go for optimal performance
  - 🎯 MCP Standard — Compatible with all MCP clients
  - RBAC support with role-based permissions
- **Warning:** Recommends using [mcpproxy](https://github.com/bivex/mcpproxy) for proxy solution
- **Open Issues:** 1
- **Last Updated:** 2026-02-17
- **[→ Repository](https://github.com/bivex/kanboard-mcp)**

---

### ⭐ [ZenTaoMcp](https://github.com/bivex/ZenTaoMcp)
- **Language:** Go 1.23+
- **Stars:** ⭐ 2 | **Forks:** 🍴 1
- **License:** MIT
- **Description:** Comprehensive MCP server that provides seamless integration between AI assistants and ZenTao project management system
- **Key Features:**
  - 🚀 **518 MCP Tools** — Complete CRUD operations for all ZenTao entities
  - 📦 **46 MCP Resources** — URI-based data access with RESTful patterns
  - 🔧 **100 Resource Templates** — Dynamic resource access with parameterized URIs
  - 💡 **2 MCP Prompts** — Guided workflows for common operations
  - 🔐 App-based and session-based authentication methods
  - 📊 Full API Coverage — Products, projects, stories, tasks, bugs, tests, releases, builds
  - Kanban boards and AI integration (ZAI)
  - Node Management (Zanode), Documentation, BI
  - 📝 Comprehensive Logging for debugging
  - ⚡ High Performance with Go
- **ZenTao Version:** 21.7.7
- **Open Issues:** 0
- **Last Updated:** 2026-01-06
- **[→ Repository](https://github.com/bivex/ZenTaoMcp)**

---

### ⭐ [archi-mcp](https://github.com/bivex/archi-mcp)
- **Language:** Python 3.11+
- **Stars:** ⭐ 0 | **Forks:** 🍴 0
- **License:** MIT
- **Dependencies:** FastMCP 2.8+, PlantUML 1.2025.4
- **Description:** AI-powered MCP server for automated ArchiMate diagram generation and enterprise architecture modeling
- **Key Features:**
  - 🏗️ Complete ArchiMate 3.2 Compliance — 55+ element types across all 7 layers
    - Motivation, Strategy, Business, Application, Technology, Physical, Implementation & Migration
  - 🎨 Automated PlantUML Diagram Generation — Professional visualization with official sprites
  - 🤖 AI-Powered Input Intelligence — Case-insensitive processing with auto-correction
  - 🛡️ Enterprise-Grade Validation Pipeline — 4-step comprehensive validation
  - 🖼️ Production-Ready Diagram Export — PNG/SVG with headless rendering
  - 🌐 Live HTTP Server — Instant diagram viewing
  - 📚 2 MCP Tools + 5 Expert AI Prompts — Architecture modeling, capability mapping
  - ✅ Production-Quality Testing — 201 test cases with 59% coverage
  - 🌍 Multi-Language Support — Automatic Slovak/English detection
  - 📊 Advanced Visualization Controls — Layout, spacing, grouping, styling
  - 🎯 Live Demo — Complete architectural blueprint included
  - 📱 Claude Code & Claude Desktop Compatible (v1.0.2+)
- **Requirements:** uv, PlantUML JAR, Graphviz
- **Last Updated:** 2025-12-18
- **[→ Repository](https://github.com/bivex/archi-mcp)**

---

### ⭐ [ILSpy-Mcp](https://github.com/bivex/ILSpy-Mcp)
- **Language:** C#
- **Stars:** ⭐ 3 | **Forks:** 🍴 1
- **License:** MIT
- **Description:** MCP server providing .NET assembly decompilation and analysis capabilities
- **Architecture:** Clean architecture with clear separation of concerns
  - **Domain** — Core business logic and entities
  - **Application** — Use cases and application services
  - **Infrastructure** — External system adapters (ILSpy, file system)
  - **Transport** — MCP protocol layer
- **Capabilities:**
  - Decompile types, methods, and assemblies
  - List and search types in assemblies
  - Analyze assembly structure and architecture
  - Find type hierarchies and relationships
  - Discover extension methods
  - Search members by name
- **Security:**
  - All operations are read-only (no file modifications)
  - Assembly path validation
  - Timeout and cancellation support
  - Request context propagation
- **Last Updated:** 2026-02-19
- **[→ Repository](https://github.com/bivex/ILSpy-Mcp)**

---

## Other MCP Servers

### [DiagSession-Mcp](https://github.com/bivex/DiagSession-Mcp)
- **Language:** C#
- **License:** MIT
- **Description:** Production-grade MCP server for analyzing Windows ETL trace files from .diagsession archives
- **Architecture:** Clean architecture principles with enterprise best practices
- **Key Features:**
  - .NET 9 console application
  - Load symbols and produce Visual Studio–style performance summaries
  - Inspect ETL/DiagSession traces
- **[→ Repository](https://github.com/bivex/DiagSession-Mcp)**

---

### [mcp-logic](https://github.com/bivex/mcp-logic)
- **Language:** Python
- **License:** MIT
- **Description:** Fully functional AI Logic Calculator utilizing Prover9/Mace4 via Python-based MCP Server
- **Key Features:**
  - First-order logic theorem proving
  - Prover9/Mace4 integration
  - Tool for Windows Claude App and other MCP clients
- **[→ Repository](https://github.com/bivex/mcp-logic)**

---

### [mcp-bpmn](https://github.com/bivex/mcp-bpmn)
- **Language:** TypeScript
- **Description:** BPMN diagram generation via MCP
- **[→ Repository](https://github.com/bivex/mcp-bpmn)**

---

### [binary_ninja_mcp](https://github.com/bivex/binary_ninja_mcp)
- **Language:** Python
- **Description:** Binary Ninja plugin containing an MCP server that enables seamless integration with your favorite LLM/MCP client
- **[→ Repository](https://github.com/bivex/binary_ninja_mcp)**

---

### [MCP-Shared-Memory](https://github.com/bivex/MCP-Shared-Memory)
- **Language:** C#
- **Description:** Share data in memory for MCP servers
- **[→ Repository](https://github.com/bivex/MCP-Shared-Memory)**

---

## MCP Integrations with Other Projects

### [staruml-controller](https://github.com/bivex/staruml-controller)
- **Language:** JavaScript
- **Description:** StarUML controller for MCP integration
- **Recent Features:**
  - Auto-expand frame to 8 legacy handlers (ERD entity/relationship, SEQ lifeline/message, etc.)
  - Extend dagre layout skip list for spatial diagrams (UMLTiming, UMLUseCase, AWS/Azure/GCP)
  - Regenerated api.html with complete endpoint summary
  - Fix wireframe frame detection, list deduplication, text escape handling
- **Last Updated:** 2026-02-17
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
| **Total MCP Servers** | 9+ |
| **Total Stars** | 24 |
| **Total Forks** | 9 |
| **Languages** | Go, Python, C#, TypeScript, JavaScript |
| **Production Ready** | 4+ (kanboard-mcp, ZenTaoMcp, archi-mcp, ILSpy-Mcp) |
| **Most Popular** | kanboard-mcp (19⭐, 7🍴) |

---

## Quick Start Patterns

Most MCP servers follow similar patterns:

### Go-based (kanboard-mcp, ZenTaoMcp)
```bash
git clone https://github.com/bivex/REPO.git
cd REPO
export API_ENDPOINT="https://your-service/api"
export API_KEY="your-api-key"
go build -o REPO .
./REPO
```

### Python-based (archi-mcp, mcp-logic)
```bash
git clone https://github.com/bivex/REPO.git
cd REPO
uv sync  # or pip install -r requirements.txt
python -m REPO
```

### C#-based (ILSpy-Mcp, DiagSession-Mcp)
```bash
git clone https://github.com/bivex/REPO.git
cd REPO
dotnet build
dotnet run
```

---

**[⬅️ Back to Inventory](../README.md)**
