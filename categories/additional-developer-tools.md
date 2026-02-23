# 🛠️ Additional Developer Tools

> Extra developer tools discovered in extended inventory (8+ projects)

---

## Featured Tools

### [GoInterruptPolicy](https://github.com/bivex/GoInterruptPolicy)
- **Description:** Attempted to create a better version of "Interrupt Affinity Policy" and "MSI Mode" Tool
- **Stars:** [![GitHub stars](https://img.shields.io/github/stars/spddl/GoInterruptPolicy.svg)](https://github.com/spddl/GoInterruptPolicy/stargazers)
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
- **Description:** Simple WinDbg extension that scans data structures for which you do not have private symbols
- **Type:** WinDbg Extension (.dll)
- **Purpose:** Try to find interesting data in structures without private symbols
- **Installation:**
  - Copy `structscan.dll` to `winext` subdirectory of WinDbg installation
  - Alternatively, copy to `%LOCALAPPDATA%\Dbg\UserExtensions`
  - Load extension: `!load structscan.dll`
- **Usage Notes:**
  - Useful for undocumented or custom structures
  - Can scan custom application's structures in real-time
  - Watch development video: https://www.youtube.com/watch?v=d1uT8tmnhZI
- **[→ Repository](https://github.com/bivex/structscan)**

---

### [react-devtools](https://github.com/bivex/react-devtools)
- **Description:** React developer tools
- **[→ Repository](https://github.com/bivex/react-devtools)**

---

### [YDArk](https://github.com/bivex/YDArk)
- **Description:** Yet Another Dark (YDArk)
- **Type:** Driver/Security Tool
- **Disclaimer:**
  > Free software. Packed with VMProtect (false antivirus positives).
  > For learning and communication only.
  > Forbidden for commercial or malicious purposes.
- **Key Features:**
  - **Process Management:**
    - Threads: View/Kill/Suspend/Resume
    - Modules: View/Unload/Dump
    - Handles: View/Close/Modify Granted Access
  - **Windows Management:**
    - View/Show/Hide/Maximized/Minimized/Enable/Disable/Close/Attack
  - **Kernel Operations:**
    - Memories: View/Dump/Modify Protection
    - Timers: View/Remove
    - System Notify: View/Remove/Disassembling
  - **Driver Module:**
    - Driver: View/Unload/Dump/View Hide Driver
  - **System Features:**
    - Filter Driver: View/Remove/Disassembling
    - DPC Timer: View/Remove/Disassembling
    - HAL Call: View/Restore/Disassembling
    - WDF Call: View/Restore/Disassembling
    - File System: View/Remove/Disassembling
    - Object Hijack: View/Restore (Disk)
  - **Global Descriptor Table:** View
- **Screenshots:** Process Screenshot, System Notify Screenshot
- **Notes:**
  - Driver doesn't support kernel isolation
  - Driver not signed — sign yourself or enable debug mode
  - Contact: QQ: 3269334485; QQ Group: 399309204
- **[→ Repository](https://github.com/bivex/YDArk)**

---

### [JustAssembly](https://github.com/bivex/JustAssembly)
- **Description:** Assembly analysis
- **[→ Repository](https://github.com/bivex/JustAssembly)**

---

### [GitHub-Repo-Visualizer](https://github.com/bivex/GitHub-Repo-Visualizer)
- **Languages:** HTML5, CSS3, JavaScript
- **Description:** Modern, interactive web application for visualizing and managing GitHub repositories
- **Key Features:**
  - 📊 **Repository Management:**
    - Complete repository overview in organized interface
    - Dual view modes: card view and table view
    - Real-time search with live filtering
    - Advanced filtering by language, topics
  - 🎯 **Smart Sorting & Analysis:**
    - Sort by: Last Updated, Most Stars, Most Forks, Name, License
    - Multiple sort options with different perspectives
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

## Summary

| Metric | Count |
|--------|-------|
| **Total Additional Developer Tools** | 8+ |
| **Languages** | Python, C/C++, JavaScript, HTML, CSS |
| **Key Areas** | Debugging, Reflection, Assembly, React, Security, Visualization |

---

**[⬅️ Back to Main Developer Tools](./developer-tools.md)**
