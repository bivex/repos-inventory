# 🔒 Security & Reverse Engineering Tools

> Tools for security analysis, reverse engineering, and system-level operations

---

## Featured Projects

### [AgentCgroup](https://github.com/bivex/AgentCgroup)
- **Language:** C
- **Alternative Name:** AgentSight (eunomia-bpf/agentsight)
- **License:** MIT
- **Description:** Zero-Instrumentation LLM Agent Observability with eBPF
- **Key Features:**
  - ✨ **Zero Instrumentation Required** — No code changes, no new dependencies, no SDKs
  - 🔍 Observes at system boundary using eBPF technology
  - 🚀 Minimal performance overhead
  - 📊 Comprehensive insights into AI agent interactions
  - 🔐 Captures encrypted traffic (raw unencrypted requests/responses)
  - 👁️ Tracks subprocess executions and file operations
  - 📈 Real-time process tree visualization
  - ⏱️ Timeline visualization for agent interactions
  - 📊 Metrics visualization (memory, CPU usage)
- **Quick Start:**
  ```bash
  wget https://github.com/eunomia-bpf/agentsight/releases/latest/download/agentsight && chmod +x agentsight
  # Record agent behavior from claude
  sudo ./agentsight record -c "claude"
  # Record agent behavior from gemini-cli
  sudo ./agentsight record -c "node"
  # For Python AI tools
  sudo ./agentsight record -c "python"
  # Visit http://127.0.0.1:7395 to view recorded data
  ```
- **Why AgentSight?**
  - Framework Adoption: Drop-in daemon vs new SDK/proxy per framework
  - Closed-Source Tools: Complete visibility into operations
  - Dynamic Agent Behavior: Kernel-level hooks for reliable monitoring
  - Encrypted Traffic: Captures real unencrypted requests/responses
  - System Interactions: Tracks all subprocess executions & file operations
  - Multi-Agent Systems: Global correlation and analysis
- **[→ Repository](https://github.com/bivex/AgentCgroup)**

---

### [pyp0f](https://github.com/bivex/pyp0f)
- **Language:** Python
- **Description:** p0f v3 with impersonation spoofing, written in Python
- **Key Features:**
  - Accurately guess the OS of a packet
  - Passive fingerprinting
  - Impersonation spoofing capabilities
  - Based on p0f v3
- **[→ Repository](https://github.com/bivex/pyp0f)**

---

### [Kage](https://github.com/bivex/Kage)
- **Language:** PHP
- **Stars:** ⭐ 3 | **Forks:** 🍴 2
- **Description:** Comprehensive PHP code encryption and protection tool designed to secure PHP source code through advanced encryption techniques
- **Key Features:**
  - 🔐 **Bytecode-Level Encryption** — Encrypt PHP code at Zend opcode level for maximum protection
  - 🔒 **Advanced Encryption** — Military-grade algorithms (XOR, AES, ROTATE)
  - 🎭 **Self-Decrypting Files** — Generate executable files that decrypt themselves at runtime
  - 🛡️ **Secure Execution Environment** — Isolated runtime preventing code tampering
  - ⚡ **C Extension Support** — High-performance native extension for demanding applications
  - ✅ **Comprehensive Testing** — Full test suite ensuring reliability
  - 👻 **Source Code Obfuscation** — Complete hiding of original PHP source code
- **Purpose and Benefits:**
  - **Intellectual Property Protection** — Encrypt sensitive business logic and algorithms
  - **License Compliance** — Prevent unauthorized code modification and redistribution
  - **Runtime Security** — Execute encrypted code in a secure, sandboxed environment
  - **Performance Optimization** — Optional C extension for enhanced performance
  - **Deployment Flexibility** — Support for traditional hosting and cloud environments
- **Bytecode Encryption Technology:**
  - Encrypts PHP code after compilation into Zend opcodes (intermediate representation)
  - Original PHP source code is completely hidden
  - Code decrypts itself during execution without exposing keys
  - Multi-algorithm support (XOR, AES, ROTATE)
  - Tamper-resistant encrypted opcodes prevent static analysis attacks
- **Intended Audience:**
  - PHP developers seeking to protect their source code
  - System administrators deploying encrypted PHP applications
  - DevOps engineers integrating Kage into CI/CD pipelines
  - Security professionals implementing code protection strategies
- **[→ Repository](https://github.com/bivex/Kage)**

---

### [smbios-parser](https://github.com/bivex/smbios-parser)
- **Language:** C99, C++98
- **Description:** Small C99 and C++98 library to parse SMBIOS information
- **Compatibility:**
  - C99 standard compliance
  - C++98 standard compliance
  - Lightweight library
- **Last Updated:** 2026-02-22
- **[→ Repository](https://github.com/bivex/smbios-parser)**

---

## Reverse Engineering & Analysis

### [EtwEventParser](https://github.com/bivex/EtwEventParser)
- **Language:** C#
- **Description:** A clean architecture, DDD-based solution for parsing ETW (Event Tracing for Windows) ETL files
- **[→ Repository](https://github.com/bivex/EtwEventParser)**

---

### [DiagSession-Mcp](https://github.com/bivex/DiagSession-Mcp)
- **Language:** C#
- **Description:** Production-grade MCP server for analyzing Windows ETL trace files from .diagsession archives
- **Key Features:**
  - .NET 9 console application
  - Load symbols and produce Visual Studio–style performance summaries
- **[→ Repository](https://github.com/bivex/DiagSession-Mcp)**

---

### [DiagSessionAnalyzer](https://github.com/bivex/DiagSessionAnalyzer)
- **Language:** C#
- **Description:** DiagSession Analyzer is a .NET 9 console application for inspecting ETL/DiagSession traces, loading symbols, and producing Visual Studio–style performance summaries
- **[→ Repository](https://github.com/bivex/DiagSessionAnalyzer)**

---

### [x64dbgMCP-Reworked](https://github.com/bivex/x64dbgMCP-Reworked)
- **Language:** C++
- **Description:** Model Context Protocol for x64dbg & x32dbg
- **Key Features:**
  - x64dbg integration
  - x32dbg integration
  - MCP protocol support
- **[→ Repository](https://github.com/bivex/x64dbgMCP-Reworked)**

---

### [binary_ninja_mcp](https://github.com/bivex/binary_ninja_mcp)
- **Language:** Python
- **Description:** Binary Ninja plugin containing an MCP server that enables seamless integration with your favorite LLM/MCP client
- **[→ Repository](https://github.com/bivex/binary_ninja_mcp)**

---

### [funcap-ida9](https://github.com/bivex/funcap-ida9)
- **Language:** Python
- **Description:** Update funcap to be able to run in ida 9.1
- **[→ Repository](https://github.com/bivex/funcap-ida9)**

---

## Performance & Monitoring

### [redesigned-octo-adventure](https://github.com/bivex/redesigned-octo-adventure)
- **Language:** C
- **Description:** libreactor server via DDD and steroids. Easy 150k rps
- **[→ Repository](https://github.com/bivex/redesigned-octo-adventure)**

---

### [sturdy-winner](https://github.com/bivex/sturdy-winner)
- **Language:** C
- **Description:** libreactor server via DDD
- **[→ Repository](https://github.com/bivex/sturdy-winner)**

---

### [turbo-octo-fishstick](https://github.com/bivex/turbo-octo-fishstick)
- **Language:** Python
- **Description:** SignFinder via DDD, and new mode VM scan
- **[→ Repository](https://github.com/bivex/turbo-octo-fishstick)**

---

## Windows Tools

### [VtSDK](https://github.com/bivex/VtSDK)
- **Language:** C#
- **Description:** Virtual Desktop C# SDK
- **[→ Repository](https://github.com/bivex/VtSDK)**

---

### [System-Audio-Recorder](https://github.com/bivex/System-Audio-Recorder)
- **Language:** C#
- **Description:** WPF приложение для одновременной записи системного звука и звука с микрофона в один файл (WAV или MP3)
- **Translation:** WPF application for simultaneous recording of system audio and microphone audio to one file (WAV or MP3)
- **[→ Repository](https://github.com/bivex/System-Audio-Recorder)**

---

### [CppPointerVisualizer](https://github.com/bivex/CppPointerVisualizer)
- **Language:** C#
- **Description:** C++ Pointer Visualizer by WPF
- **[→ Repository](https://github.com/bivex/CppPointerVisualizer)**

---

### [FrameProExample-60FPS](https://github.com/bivex/FrameProExample-60FPS)
- **Language:** C++
- **Description:** FrameProExample fixed by FramePro-MCP
- **[→ Repository](https://github.com/bivex/FrameProExample-60FPS)**

---

## Summary

| Metric | Count |
|--------|-------|
| **Total Security Tools** | 17+ |
| **Languages** | C, Python, PHP, C#, C++ |
| **Key Areas** | eBPF, fingerprinting, code protection, ETL parsing, reverse engineering |
| **Most Popular** | Kage (3⭐, 2🍴) |

---

## Key Highlights

- **AgentCgroup/AgentSight** — Unique eBPF-based zero-instrumentation observability for LLM agents
- **Kage** — Advanced PHP bytecode encryption with military-grade algorithms
- **pyp0f** — Passive OS fingerprinting in Python
- **Multiple MCP integrations** — ILSpy, Binary Ninja, x64dbg, DiagSession

---

**[⬅️ Back to Inventory](../README.md)**
