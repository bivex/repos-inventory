# 🔌 Additional MCP Servers

> Extra MCP servers discovered in extended inventory (20+ projects)

---

## Featured MCP Servers

### [WinReg-Mcp](https://github.com/bivex/WinReg-Mcp)
- **Language:** Go (1.21+)
- **Description:** Production-ready MCP server for Windows Registry access
- **Architecture:** Clean, layered architecture with strict separation of concerns
  ```
  MCP Protocol Layer → Application/Use-Case Layer → Domain Layer → Infrastructure Layer
  ```
- **Core Capabilities:**
  - ✅ Read Registry Values with path validation
  - ✅ Enumerate Keys and Values
  - ✅ Write Registry Values with authorization
  - ✅ Delete Registry Items with permission controls
  - ✅ Query Key Metadata (modification time, value count)
- **Security Features:**
  - 🔒 Path Allow-List — Only configured registry paths accessible
  - 🔒 Authorization Levels — READ_ONLY, READ_WRITE, ADMIN
  - 🔒 Data Exfiltration Protection — Limits on enumeration depth
  - 🔒 Audit Logging — All operations logged with correlation IDs
  - 🔒 Rate Limiting — Configurable request rate limits
  - 🔒 Timeout Controls — Execution time limits
- **Observability:**
  - 📊 Prometheus-compatible metrics
  - 📝 Structured JSON logging
  - 🏥 Health checks (liveness, readiness, startup)
- **[→ Repository](https://github.com/bivex/WinReg-Mcp)**

---

### [carla-mcp-server](https://github.com/bivex/carla-mcp-server)
- **Language:** Python 3.12+
- **Description:** Comprehensive MCP server for complete Carla audio plugin control
- **Key Features:**
  - 🤖 AI-Native — Designed for natural language control through LLMs
  - 🎛️ Complete Control — 45 tools covering every aspect of audio production
  - ⚡ Real-Time — Low-latency monitoring and analysis
  - 🧪 Professional — Production-ready with error handling
  - 📈 Scalable — Modular architecture
- **What You Can Do:**
  - "Load my mixing project and set up a drum bus with compression"
  - "Create a filter sweep effect on the lead synth, sync it to tempo"
  - "Analyze my mix and suggest improvements"
  - "Prepare this session for live performance with low latency"
- **Tools Categories (7 total):**
  1. 🗂️ Session Management (8 tools) — Load/save projects, A/B snapshots, hot-swap
  2. 🔌 Plugin Control (8 tools) — VST2/3, LV2, LADSPA, DSSI, AU, SF2/SFZ
  3. 🔗 Audio Routing (7 tools) — Complex routing matrix, bus creation
  4. 🎚️ Parameter Automation (8 tools) — Automation, MIDI CC mapping, macros
  5. 📊 Real-Time Analysis (5 tools) — Real-time monitoring
  6. 🎨 Effects Management (5 tools) — Create/apply effects
  7. 🚀 Performance Optimization (7 tools) — CPU monitoring, latency
- **[→ Repository](https://github.com/bivex/carla-mcp-server)**

---

### [FramePro-MCP](https://github.com/bivex/FramePro-Mcp)
- **Language:** Go 1.21+
- **Description:** MCP server for analyzing FramePro profiling data with senior-level performance optimization insights
- **Features:**
  - **4 Analysis Tools:**
    1. `analyze_performance` — CPU hotspots, frame issues, thread saturation
    2. `find_hotspots` — Top N most expensive functions (ranked by time)
    3. `analyze_frame_times` — Frame performance analysis (FPS estimation, spikes)
    4. `compare_profiles` — Profile comparison (regressions, improvements)
  - **Expert Analysis:**
    - Thread-Aware — Identifies Main, Render, Worker threads
    - Pattern Recognition — Detects Wait, Lock, Physics, Render, Update patterns
    - Variance Analysis — Finds inconsistent performance (stuttering)
    - Automatic Prioritization — Critical issues flagged first
- **Focus Areas:** `cpu`, `frames`, `threads`, or `all`
- **Installation:** Built executable available at:
  ```
  c:\Program Files\PureDevSoftware\FramePro\FrameProReader\FramePro-MCP\framepro-mcp.exe
  ```
- **[→ Repository](https://github.com/bivex/FramePro-Mcp)**

---

### [MemPro-mcp](https://github.com/bivex/MemPro-mcp)
- **Language:** Go 1.22+
- **Description:** MCP server for analyzing MemPro memory profiling data and detecting memory errors using AI
- **Features:**
  - **6 MCP Tools:**
    1. `analyze_leaks` — Memory leaks analysis (severity, descriptions, suggestions)
    2. `get_summary` — Memory usage summary with metrics
    3. `get_top_leakers` — Top N functions causing leaks (default: 10)
    4. `analyze_fragmentation` — Memory fragmentation analysis
    5. `find_large_allocations` — Unusually large allocations
    6. `get_all_issues` — Complete analysis (summary, leaks, fragmentation, allocations)
  - **MCP Resources:**
    - `mempro://stats` — Quick access to memory statistics in JSON
- **Prerequisites:**
  - Go 1.22+ installed
  - MemPro JSON exports
- **[→ Repository](https://github.com/bivex/MemPro-mcp)**

---

### [git-mcp-server](https://github.com/bivex/git-mcp-server)
- **Language:** TypeScript 5.8.3
- **Version:** 2.1.2
- **License:** Apache 2.0
- **Status:** Stable
- **Built on:** cyanheads/mcp-ts-template
- **Description:** MCP server providing Git operations (clone, commit, push, pull, branch, diff, log, status)
- **Key Features:**
  - 🤖 Empower AI agents with seamless Git integration
  - 🔧 Automate Git workflows — Clone, create branches, commit, push, tags
  - 📊 Repository insights — Status, logs, diffs, Git objects
  - 🛡️ Secure execution via Node.js child_process
  - 🔐 Commit Signing — GPG/SSH signing for verified commits
  - 📂 Working Directory Management — Session-specific working directory
  - ⚠️ Safety Features — Confirmation for destructive operations
  - 📝 Structured Logging with sensitive data redaction
  - 🧪 Robust error handling with McpError types
  - 🧪 Input Validation with Zod schemas
  - 🌐 HTTP Transport Option with Express server, SSE, CORS
- **[→ Repository](https://github.com/bivex/git-mcp-server)**

---

### [reaper-reapy-mcp](https://github.com/bivex/reaper-reapy-mcp)
- **Language:** Python 3.10+
- **Description:** MCP server for controlling REAPER Digital Audio Workstation through AI assistants
- **Key Features:**
  - ✨ **104+ Specialized Tools:**
    - 🎛️ Track Management — Create, rename, color, volume, pan, mute, solo, record arm
    - 🎚️ FX Control — Add/remove effects, parameter automation, compressor/limiter presets
    - 🎹 MIDI Operations — Create items, add/edit notes, pitch filtering, musical positioning
    - 🎧 Audio Processing — Insert files, duplicate items, split, fade, crossfade
    - 🔗 Routing & Mixing — Sends/receives, folder tracks, bus creation, comprehensive routing
    - 🎚️ Sidechain & Bus — Sidechain compression, parallel processing, saturation buses
    - 🎛️ Automation — Envelope creation, point editing, automation modes
    - 🎯 Project Control — Tempo, markers, regions, master track, project clearing
    - 📊 Audio Analysis — LUFS/loudness measurement, spectrum analysis, stereo imaging
    - 🎵 Mastering Tools — LUFS normalization, broadcast compliance, streaming standards
    - 📈 Gain Staging — Volume automation, clip gain, peak limiting
    - 🎚️ Monitoring — Peak metering, crest factor, phase correlation
    - 🎵 Dual Positioning — Time and musical notation support
- **Prerequisites:**
  - Python 3.10+
  - REAPER DAW installed
  - Enable ReaScript and configure Python path
- **[→ Repository](https://github.com/bivex/reaper-reapy-mcp)**

---

### [easyprofiler-mcp](https://github.com/bivex/easyprofiler-mcp)
- **Language:** Go
- **Description:** MCP server for analyzing EasyProfiler profiles (.prof files)
- **Key Features:**
  - ✅ Протестировано на реальном 160MB файле с 6M+ блоками
  - ⚡ Готов к использованию с Claude Desktop
  - **5 Tools:**
    1. `load_profile` — Загружает .prof файл для анализа
    2. `get_slowest_blocks` — Топ самых медленных блоков (default: 10)
    3. `get_thread_statistics` — Статистика использования времени по потокам
    4. `get_hotspots` — Горячие точки (функции с наибольшим временем)
    5. `analyze_performance_issues` — Комплексный анализ проблем (блокировки, дисбаланс, контекст)
- **[→ Repository](https://github.com/bivex/easyprofiler-mcp)**

---

### [verysleepy-mcp](https://github.com/bivex/verysleepy-mcp)
- **Language:** Go
- **Description:** Professional MCP server for analyzing Very Sleepy CPU profiles (.sleepy files) with 40 years of senior engineering wisdom
- **Key Features:**
  - 🎯 Purpose: Deep performance analysis without manual inspection
  - 🏗️ Architecture: Clean separation of concerns (parsing isolated from analysis)
  - 🔧 Design Principles:
    - Separation of concerns
    - No external dependencies for core (parser uses stdlib)
    - Caching for efficiency
    - O(n) algorithms where possible
  - **8 Tools:**
    1. `load_profile` — Load and validate .sleepy profile
    2. `find_hotspots` — Top N functions consuming most CPU time
    3. `find_bottom_functions` — Bottom functions analysis
    4. `analyze_modules` — Module analysis
    5. `detect_issues` — Issue detection
    6. `get_statistics` — Statistical analysis
    7. `view_callstack` — View callstack
    - And more...
- **Focus Areas:** CPU bottlenecks, callstack analysis, module performance
- **[→ Repository](https://github.com/bivex/verysleepy-mcp)**

---

### [mcp-discord](https://github.com/bivex/mcp-discord)
- **Language:** Node.js v16+
- **Description:** MCP server for interacting with Discord platform
- **Key Features:**
  - 🤖 **Bot Operations:**
    - Login to Discord bot
    - List servers bot is a member of
    - Get server information
  - 💬 **Message Management:**
    - Search messages in server
    - Read/delete channel messages
    - Send messages to specified channels (IDs or names)
  - 📰 **Forum Management:**
    - Retrieve forum channel lists
    - Create/delete/reply to forum posts
    - Create/delete text channels
  - 😀 **Reactions:**
    - Add/remove message reactions
  - 🪝 **Webhooks:**
    - Create/delete/use webhooks
- **Requirements:**
  - Node.js 16+ and npm 7+
  - Discord bot token
  - Bot permissions (Message Content, Server Members, Presence intents enabled)
  - Server permissions: Administrator (recommended) or specific permissions
- **Integration:** Listed on glama.ai MCP servers directory
- **[→ Repository](https://github.com/bivex/mcp-discord)**

---

### [mcpWinAudit](https://github.com/bivex/mcpWinAudit)
- **Language:** C#
- **Description:** Windows Audit MCP — Analyzes Windows System Event Log and performance
- **Key Features:**
  - 🔍 **11 Commands:**
    1. `AnalyzeStartupLogs()` — Analyzes System Event Log for startup errors/warnings
    2. `CheckFilePermissions(filePath)` — Checks access permissions
    3. `CreateDirectory(path)` — Creates directory
    4. `DeleteDirectory(path)` — Deletes directory
    5. `GetCurrentDirectory()` — Gets current working directory
    6. `GetLast1DaysFailedSystemEvents()` — Retrieves error events from last 1 day
    7. `GetTop15PerformanceImpactingProcesses()` — Top 15 processes by CPU/memory
    8. `ListAllProcesses()` — Lists all running processes with performance info
    9. `ListFiles(path, recursive)` — Lists files/directories
    10. `MoveDirectory(sourcePath, destinationPath)` — Moves directory
    11. `MoveFile(sourcePath, destinationPath)` — Moves file
    12. `RenameFile(oldPath, newPath)` — Renames file
  - **Audited with:** 🔍 Smithery badge
- **[→ Repository](https://github.com/bivex/mcpWinAudit)**

---

### [DnSpy-MCPserver-Extension](https://github.com/bivex/DnSpy-MCPserver-Extension)
- **Language:** C#
- **Description:** dnSpy MCP Extension
- **[→ Repository](https://github.com/bivex/DnSpy-MCPserver-Extension)**

---

### [mcpWinAuditServer](https://github.com/bivex/mcpWinAuditServer)
- **Language:** C#
- **Description:** Windows Audit MCP Server
- **[→ Repository](https://github.com/bivex/mcpWinAuditServer)**

---

### [x64DbgMCPServer](https://github.com/bivex/x64DbgMCPServer)
- **Language:** C#
- **Description:** x64dbg MCP Server
- **[→ Repository](https://github.com/bivex/x64DbgMCPServer)**

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

### [ida_pro_scripts](https://github.com/bivex/ida_pro_scripts)
- **Description:** IDA Pro scripts
- **[→ Repository](https://github.com/bivex/ida_pro_scripts)**

---

## Summary

| Metric | Count |
|--------|-------|
| **Total Additional MCP Servers** | 20+ |
| **Languages** | Go, Python, TypeScript, ? |
| **Key Categories** | Windows, Audio, Performance, Memory, Git, Debug |

---

**[⬅️ Back to Main MCP Servers](./mcp-servers.md)**
