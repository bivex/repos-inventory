# 💎 Useful Code Projects (Non-ISO)

> Projects with useful code but NOT containing "iso" in name

---

## Featured Projects

### [AgentCgroup](https://github.com/bivex/AgentCgroup)
- **Language:** C
- **Description:** AgentSight: Zero-Instrumentation LLM Agent Observability with eBPF
- **Key Features:**
  - ✨ Zero Instrumentation Required — No code changes, no new dependencies, no SDKs
  - 🔍 Observes at system boundary using eBPF technology
  - 🚀 Minimal performance overhead
  - 📊 Comprehensive insights into AI agent interactions
  - 🔐 Captures encrypted traffic (raw unencrypted requests/responses)
  - 👁️ Tracks subprocess executions and file operations
  - 📈 Real-time process tree visualization
  - ⏱️ Timeline visualization for agent interactions
  - 📊 Metrics visualization (memory, CPU usage)
- **Why AgentSight?**
  - Framework Adoption: Drop-in daemon vs new SDK/proxy per framework
  - Closed-Source Tools: Complete visibility into operations
  - Dynamic Agent Behavior: Kernel-level hooks for reliable monitoring
  - Encrypted Traffic: Captures real unencrypted requests/responses
  - System Interactions: Tracks all subprocess behaviors & file operations
  - Multi-Agent Systems: Global correlation and analysis
- **Quick Start:**
  ```bash
  wget https://github.com/eunomia-bpf/agentsight/releases/latest/download/agentsight && chmod +x agentsight
  sudo ./agentsight record -c "claude"
  ```
- **[→ Repository](https://github.com/bivex/AgentCgroup)**

---

### [Kage](https://github.com/bivex/Kage)
- **Language:** PHP
- **Stars:** ⭐ 3 | **Forks:** 🍴 2
- **Description:** PHP code encryption and protection tool
- **Key Features:**
  - 🔐 **Bytecode-Level Encryption** — Encrypt PHP code at Zend opcode level
  - 🔒 **Advanced Encryption** — Military-grade algorithms (XOR, AES, ROTATE)
  - 🎭 **Self-Decrypting Files** — Decrypt themselves at runtime without storing keys
  - 🛡️ **Secure Execution Environment** — Isolated runtime preventing code tampering
  - ⚡ **C Extension Support** — High-performance native extension
  - ✅ **Comprehensive Testing** — Full test suite ensuring reliability
  - 👻 **Source Code Obfuscation** — Complete hiding of original PHP source code
- **Bytecode Encryption Technology:**
  - Encrypts PHP code after compilation into Zend opcodes
  - Original PHP source code is completely hidden
  - Code decrypts itself during execution without exposing keys
  - Multi-algorithm support (XOR, AES, ROTATE)
  - Tamper-resistant encrypted opcodes prevent static analysis attacks
- **Purpose:**
  - Intellectual Property Protection — Encrypt sensitive business logic
  - License Compliance — Prevent unauthorized code modification
  - Runtime Security — Execute encrypted code in secure sandboxed environment
  - Performance Optimization — Optional C extension for enhanced performance
  - Deployment Flexibility — Support for traditional hosting and cloud environments
- **Intended Audience:**
  - PHP developers seeking to protect their source code
  - System administrators deploying encrypted PHP applications
  - DevOps engineers integrating Kage into CI/CD pipelines
  - Security professionals implementing code protection strategies
- **[→ Repository](https://github.com/bivex/Kage)**

---

### [pyp0f](https://github.com/bivex/pyp0f)
- **Language:** Python
- **Description:** p0f v3 with impersonation spoofing, written in Python
- **Key Features:**
  - 🔍 **Accurately guess the OS of a packet** — Passive fingerprinting
  - 🎭 **Impersonation spoofing capabilities**
  - **Based on p0f v3**
- **[→ Repository](https://github.com/bivex/pyp0f)**

---

### [EtwEventParser](https://github.com/bivex/EtwEventParser)
- **Language:** C#
- **Description:** Clean architecture, DDD-based solution for parsing ETW (Event Tracing for Windows) ETL files
- **[→ Repository](https://github.com/bivex/EtwEventParser)**

---

## MCP Servers (Non-ISO)

### [reaper-reapy-mcp](https://github.com/bivex/reaper-reapy-mcp)
- **Language:** Python 3.10+
- **Description:** REAPER Digital Audio Workstation MCP server
- **Key Features:**
  - 🎛️ **104+ Specialized Tools** across 7 categories
  - 🗂️ **Session Management** — Load/save projects, A/B snapshots, hot-swap
  - 🔌 **Plugin Control** — VST2/3, LV2, LADSPA, DSSI, AU, SF2/SFZ
  - 🔗 **Audio Routing** — Complex routing matrix, bus creation
  - 🎚️ **Parameter Automation** — Advanced automation, MIDI CC mapping, macros
  - 📊 **Real-Time Analysis** — Real-time monitoring
  - 🎨 **Effects Management** — Create/apply effects
  - 🚀 **Performance Optimization** — CPU monitoring, latency
- **Capabilities:**
  - Natural language control through LLMs
  - Low-latency monitoring and analysis
  - Production-ready with comprehensive error handling
- **[→ Repository](https://github.com/bivex/reaper-reapy-mcp)**

---

### [easyprofiler-mcp](https://github.com/bivex/easyprofiler-mcp)
- **Language:** Go
- **Description:** EasyProfiler MCP server
- **Key Features:**
  - **4 Analysis Tools:**
    1. `load_profile` — Load .prof file for analysis
    2. `get_slowest_blocks` — Top N most expensive functions (ranked by time)
    3. `get_thread_statistics` — Thread statistics
    4. `get_hotspots` — CPU hotspots with detailed metrics
    5. `analyze_performance_issues` — Detects CPU hotspots, frame issues, thread saturation
- **Purpose:** Profile EasyProfiler files and identify performance issues
- **[→ Repository](https://github.com/bivex/easyprofiler-mcp)**

---

### [verysleepy-mcp](https://github.com/bivex/verysleepy-mcp)
- **Language:** Go
- **Description:** Very Sleepy Profiler MCP server
- **Key Features:**
  - **Purpose:** Deep performance analysis of CPU profiles without manual inspection
  - **40 Years of Senior Engineering Wisdom**
  - **8 Tools:**
    1. `load_profile` — Load and validate .sleepy profile
    2. `find_hotspots` — Top N functions consuming most CPU time
    3. `find_bottom_functions` — Bottom functions analysis
    4. `analyze_modules` — Module analysis
    5. `detect_issues` — Issue detection
    6. `get_statistics` — Statistical analysis
    7. `view_callstack` — View callstack
- **Architecture:** Clean separation of parsing logic from analysis logic
- **[→ Repository](https://github.com/bivex/verysleepy-mcp)**

---

### [MemPro-mcp](https://github.com/bivex/MemPro-mcp)
- **Language:** Go 1.22+
- **Description:** MCP server for analyzing MemPro memory profiling data
- **Key Features:**
  - **6 MCP Tools:**
    1. `analyze_leaks` — Memory leaks with severity, descriptions
    2. `get_summary` — Memory usage summary with metrics
    3. `get_top_leakers` — Top N functions causing leaks
    4. `analyze_fragmentation` — Memory fragmentation analysis
    5. `find_large_allocations` — Unusually large allocations
    6. `get_all_issues` — Complete analysis (summary, leaks, fragmentation)
  - **Purpose:** Detect memory leaks, fragmentation, and large allocations
- **Prerequisites:** Go 1.22+ installed, MemPro JSON exports
- **[→ Repository](https://github.com/bivex/MemPro-mcp)**

---

### [git-mcp-server](https://github.com/bivex/git-mcp-server)
- **Language:** TypeScript 5.8.3
- **Version:** 2.1.2
- **License:** Apache 2.0
- **Status:** Stable
- **Description:** Git operations via MCP (clone, commit, push, pull, branch, diff, log, status)
- **Key Features:**
  - 🤖 Empower AI agents with seamless Git integration
  - 🔧 Automate Git workflows — Clone, create branches, commit, push, tags
  - 📊 Repository insights — Status, logs, diffs, Git objects
  - 🛡️ Secure execution — Node.js child_process
  - 🗂️ Working Directory Management — Session-specific working directory
  - ⚠️ Safety Features — Confirmation for destructive operations
  - 🔐 Commit Signing — GPG or SSH signing for verified commits
- **Built on:** cyanheads/mcp-ts-template
- **Core Utilities:**
  - Logging with structured output
  - Error handling with McpError types
  - Configuration via environment variables
  - Input validation with Zod schemas
  - Request context tracking
  - HTTP Transport Option with Express server, SSE, CORS
- **[→ Repository](https://github.com/bivex/git-mcp-server)**

---

## Developer Tools

### [GoInterruptPolicy](https://github.com/bivex/GoInterruptPolicy)
- **Description:** Interrupt Affinity Policy and MSI Mode Tool
- **[→ Repository](https://github.com/bivex/GoInterruptPolicy)**

---

### [ReflectionTool](https://github.com/bivex/ReflectionTool)
- **Language:** Python 3.x
- **Frameworks:** PyQt6, wikipedia-api, requests
- **Description:** Simple GUI application that allows users to fetch and view random Wikipedia articles
- **Key Features:**
  - 📖 Fetch random articles from Wikipedia
  - 📋 View article summary, sections, and categories
  - 🌍 Supports multiple Wikipedia languages
  - 🎨 Includes light and dark theme toggle
  - 🌐 GUI language can be changed
- **Requirements:**
  - Python 3.x
  - PyQt6
  - wikipedia-api
  - requests
- **Installation:**
  ```bash
  pip install PyQt6 wikipedia-api requests
  python wiki_gui_tool.py
  ```
- **[→ Repository](https://github.com/bivex/ReflectionTool)**

---

### [structscan](https://github.com/bivex/structscan)
- **Type:** WinDbg Extension (.dll)
- **Description:** WinDbg extension that scans data structures without private symbols
- **Purpose:** Find interesting data in structures where you do NOT have private symbols
- **Installation:**
  - Copy `structscan.dll` to `winext` subdirectory of WinDbg installation
  - Alternatively, copy to `%LOCALAPPDATA%\Dbg\UserExtensions`
  - Load extension: `!load structscan.dll`
- **Usage:** Scan custom application's structures in real-time
- **[→ Repository](https://github.com/bivex/structscan)**

---

### [YDArk](https://github.com/bivex/YDArk)
- **Language:** C#
- **Description:** Yet Another Dark (YDArk) — Security tool
- **Type:** Driver/Security Tool
- **Key Features:**
  - **Process Management:** Threads, Modules, Handles, Windows, Timers
  - **Driver Module:** Driver operations
  - **Kernel:** System Notify, Filter Driver, DPC Timer, HAL Call
  - **Disclaimers:**
    - Free software
    - Packed with VMProtect (false antivirus positives)
    - Forbidden for commercial use without authorization
    - For learning and communication only
    - Driver not signed — sign yourself or enable debug mode
- **[→ Repository](https://github.com/bivex/YDArk)**

---

### [GitHub-Repo-Visualizer](https://github.com/bivex/GitHub-Repo-Visualizer)
- **Languages:** HTML5, CSS3, JavaScript
- **Description:** Modern, interactive web application for visualizing and managing GitHub repositories
- **Key Features:**
  - 📊 **Repository Management:** Complete overview in organized interface
  - 🔍 **Real-time Search:** Find repositories instantly with live search
  - 🎯 **Smart Sorting:** Last Updated, Most Stars, Most Forks, Name, License
  - 🏷️ **Enhanced Repository Information:**
    - Programming language with color-coded labels
    - License information with visual indicators
    - Topics/hashtags with enhanced styling
    - Star and fork counts
    - Creation and update dates
  - 📈 **Improvement Score System:**
    - Intelligent scoring based on: Description quality, Topics, Stars, Recent updates, Language spec, License, Forks
    - Visual progress bars with color-coded indicators
    - Priority identification for repositories needing attention
  - 📋 **Export Functionality:**
    - JSON export for repositories needing improvements
    - Smart filtering (excludes private repositories)
    - Structured, well-formatted data
- **[→ Repository](https://github.com/bivex/GitHub-Repo-Visualizer)**

---

## Web & Frontend Tools

### [ThemeRevision](https://github.com/bivex/ThemeRevision)
- **Description:** Theme revision tool
- **[→ Repository](https://github.com/bivex/ThemeRevision)**

---

### [caldav-mcp](https://github.com/bivex/caldav-mcp)
- **Description:** CalDAV MCP server
- **[→ Repository](https://github.com/bivex/caldav-mcp)**

---

### [reverseTabs](https://github.com/bivex/reverseTabs)
- **Description:** Reverse tabs extension
- **[→ Repository](https://github.com/bivex/reverseTabs)**

---

### [Kanboard-Customizer-Themes](https://github.com/bivex/Kanboard-Customizer-Themes)
- **Description:** Kanboard theme customizer
- **[→ Repository](https://github.com/bivex/Kanboard-Customizer-Themes)**

---

### [pgv_faiss](https://github.com/bivex/pgv_faiss)
- **Description:** PGV FAISS
- **[→ Repository](https://github.com/bivex/pgv_faiss)**

---

### [mcpproxy](https://github.com/bivex/mcpproxy)
- **Description:** MCP proxy
- **[→ Repository](https://github.com/bivex/mcpproxy)**

---

### [back-in-a-minute](https://github.com/bivex/back-in-a-minute)
- **Description:** Quick backup tool
- **[→ Repository](https://github.com/bivex/back-in-a-minute)**

---

### [kanboard-plugin-scrumsprint](https://github.com/bivex/kanboard-plugin-scrumsprint)
- **Description:** Kanboard Scrum Sprint plugin
- **[→ Repository](https://github.com/bivex/kanboard-plugin-scrumsprint)**

---

### [awesome-mcp-servers](https://github.com/bivex/awesome-mcp-servers)
- **Description:** Awesome MCP servers list
- **[→ Repository](https://github.com/bivex/awesome-mcp-servers)**

---

## Security & Windows Tools

### [mcpWinAudit](https://github.com/bivex/mcpWinAudit)
- **Language:** C#
- **Description:** Windows Audit MCP
- **[→ Repository](https://github.com/bivex/mcpWinAudit)**

---

### [DnSpy-MCPserver-Extension](https://github.com/bivex/DnSpy-MCPserver-Extension)
- **Language:** C#
- **Description:** dnSpy MCP Extension
- **[→ Repository](https://github.com/bivex/DnSpy-MCPserver-Extension)**

---

### [x64DbgMCPServer](https://github.com/bivex/x64DbgMCPServer)
- **Language:** C#
- **Description:** x64dbg MCP Server
- **[→ Repository](https://github.com/bivex/x64DbgMCPServer)**

---

### [mcpWinAuditServer](https://github.com/bivex/mcpWinAuditServer)
- **Language:** C#
- **Description:** Windows Audit MCP Server
- **[→ Repository](https://github.com/bivex/mcpWinAuditServer)**

---

### [FrameProReader](https://github.com/bivex/FrameProReader)
- **Description:** FramePro reader
- **[→ Repository](https://github.com/bivex/FrameProReader)**

---

### [batch_files](https://github.com/bivex/batch_files)
- **Description:** Batch file utilities
- **[→ Repository](https://github.com/bivex/batch_files)**

---

### [MemProReader](https://github.com/bivex/MemProReader)
- **Description:** Memory profiler reader
- **[→ Repository](https://github.com/bivex/MemProReader)**

---

### [vixapi-csharp-bindings](https://github.com/bivex/vixapi-csharp-bindings)
- **Language:** C#
- **Description:** Vix API C# bindings
- **[→ Repository](https://github.com/bivex/vixapi-csharp-bindings)**

---

### [ida_pro_scripts](https://github.com/bivex/ida_pro_scripts)
- **Language:** ?
- **Description:** IDA Pro scripts
- **[→ Repository](https://github.com/bivex/ida_pro_scripts)**

---

### [VixMCP.Ai.Bridge](https://github.com/bivex/VixMCP.Ai.Bridge)
- **Language:** C#
- **Description:** Vix MCP AI Bridge
- **[→ Repository](https://github.com/bivex/VixMCP.Ai.Bridge)**

---

### [adb-mcp](https://github.com/bivex/adb-mcp)
- **Description:** Android Debug Bridge MCP
- **[→ Repository](https://github.com/bivex/adb-mcp)**

---

### [google-maps-mcp](https://github.com/bivex/google-maps-mcp)
- **Description:** Google Maps MCP server
- **[→ Repository](https://github.com/bivex/google-maps-mcp)**

---

### [scancodeMCP](https://github.com/bivex/scancodeMCP)
- **Description:** ScanCode MCP for code analysis
- **[→ Repository](https://github.com/bivex/scancodeMCP)**

---

### [jebmcp](https://github.com/bivex/jebmcp)
- **Description:** JEB Decompiler MCP
- **[→ Repository](https://github.com/bivex/jebmcp)**

---

### [WireMCP](https://github.com/bivex/WireMCP)
- **Description:** WireGuard MCP
- **[→ Repository](https://github.com/bivex/WireMCP)**

---

## AI & Machine Learning

### [mcp-discord](https://github.com/bivex/mcp-discord)
- **Language:** Node.js v16+
- **Description:** MCP server for interacting with Discord platform
- **Key Features:**
  - 🤖 Bot Operations — Login, list servers, get server information
  - 💬 Message Management — Search, read/delete channel messages, send messages
  - 📰 Forum Management — Retrieve forum channels, create/delete/reply posts, create/delete text channels
  - 😀 Reactions — Add/remove message reactions
  - 🪝 Webhooks — Create/delete/use webhooks
- **Requirements:**
  - Node.js 16.0+ and npm 7+
  - Discord bot token (obtainable from Discord Developer Portal)
  - Bot permissions (Message Content, Server Members, Presence intents enabled)
  - Server permissions: Administrator (recommended) or specific permissions
- **Integration:** Listed on glama.ai MCP servers directory
- **[→ Repository](https://github.com/bivex/mcp-discord)**

---

### [mcpWinAudit](https://github.com/bivex/mcpWinAudit)
- **Description:** Windows Audit MCP (repeated - may be duplicate entry)
- **[→ Repository](https://github.com/bivex/mcpWinAudit)**

---

### [DnSpy-MCPserver-Extension](https://github.com/bivex/DnSpy-MCPserver-Extension)
- **Description:** dnSpy MCP Extension (repeated - may be duplicate entry)
- **[→ Repository](https://github.com/bivex/DnSpy-MCPserver-Extension)**

---

### [x64DbgMCPServer](https://github.com/bivex/x64DbgMCPServer)
- **Description:** x64dbg MCP Server (repeated - may be duplicate entry)
- **[→ Repository](https://github.com/bivex/x64DbgMCPServer)**

---

### [mcpWinAuditServer](https://github.com/bivex/mcpWinAuditServer)
- **Description:** Windows Audit MCP Server (repeated - may be duplicate entry)
- **[→ Repository](https://github.com/bivex/mcpWinAuditServer)**

---

### [JustAssembly](https://github.com/bivex/JustAssembly)
- **Description:** Assembly analysis
- **[→ Repository](https://github.com/bivex/JustAssembly)**

---

### [react-devtools](https://github.com/bivex/react-devtools)
- **Description:** React developer tools
- **[→ Repository](https://github.com/bivex/react-devtools)**

---

## Infrastructure

### [sakura](https://github.com/bivex/sakura)
- **Description:** Sakura deployment
- **[→ Repository](https://github.com/bivex/sakura)**

---

### [Dual-N-Back](https://github.com/bivex/Dual-N-Back)
- **Description:** Dual network backup
- **[→ Repository](https://github.com/bivex/Dual-N-Back)**

---

## Personal & Misc

### [GymVision](https://github.com/bivex/GymVision)
- **Description:** Computer vision for gym
- **[→ Repository](https://github.com/bivex/GymVision)**

---

### [Audio-GD-NFB-11.38](https://github.com/bivex/Audio-GD-NFB-11.38)
- **Description:** Audio for GD/NFB (Guide Dogs for the Blind - National Federation of the Blind)
- **[→ Repository](https://github.com/bivex/Audio-GD-NFB-11.38)**

---

### [Cisco-Research](https://github.com/bivex/Cisco-Research)
- **Description:** Cisco research
- **[→ Repository](https://github.com/bivex/Cisco-Research)**

---

### [CursorPaste](https://github.com/bivex/CursorPaste)
- **Description:** Cursor paste tool
- **[→ Repository](https://github.com/bivex/CursorPaste)**

---

### [tongue_twisters](https://github.com/bivex/tongue_twisters)
- **Description:** Tongue twisters
- **[→ Repository](https://github.com/bivex/tongue_twisters)**

---

### [visual-improvements](https://github.com/bivex/visual-improvements)
- **Description:** Visual improvements
- **[→ Repository](https://github.com/bivex/visual-improvements)**

---

### [voice_to_text](https://github.com/bivex/voice_to_text)
- **Description:** Voice to text
- **[→ Repository](https://github.com/bivex/voice_to_text)**

---

## Summary

| Metric | Count |
|--------|-------|
| **Total Useful Code Projects (Non-ISO)** | 70+ |
| **Languages** | C, Python, Go, C#, PHP, TypeScript, HTML5, CSS, JavaScript, Node.js |
| **Key Categories** |
  - MCP Servers (7+): reaper, easyprofiler, verysleepy, MemPro, git-mcp, discord |
  - Security Tools (4+): Kage (PHP encryption), pyp0f, YDArk, EtwEventParser |
  - Developer Tools (5+): GoInterruptPolicy, ReflectionTool, structscan, GitHub-Repo-Visualizer |
  - Web Tools (10+): ThemeRevision, caldav-mcp, reverseTabs, Kanboard themes, pgv_faiss |
  - Windows Tools (10+): mcpWinAudit, DnSpy, x64dbg, FrameProReader, batch files, MemProReader |
  - AI/ML (4+): discord, GymVision, Audio-GD-NFB, Cisco-Research |
  - Infrastructure (2): sakura, Dual-N-Back |
  - Personal/Misc (7+): CursorPaste, tongue twisters, visual improvements, voice to text |

---

**[⬅️ Back to Main README](./README.md)**
