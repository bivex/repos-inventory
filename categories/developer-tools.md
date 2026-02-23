# 🛠️ Developer Tools

> Code analysis, quality tools, and developer utilities

---

## Featured Projects

### [tsPro](https://github.com/bivex/tsPro)
- **Language:** TypeScript
- **Description:** Hexagonal DDD Analyzer: Enterprise-grade static analysis tool for TypeScript/Angular projects
- **Key Features:**
  - ⚡ **High Performance & Parallel Processing**
    - Parallel file analysis with configurable concurrency
    - Real-time progress reporting during analysis
    - CPU-aware defaults (automatically detects available cores)
    - Configurable limits to prevent resource exhaustion
  - 📋 **Comprehensive Console Output**
    - Summary at beginning with key metrics
    - Final summary at end with quality progress bar
    - Color-coded severity levels (red/yellow/blue)
    - Categorized violation breakdown (SOLID, DDD, Architecture, Security)
  - 🏗️ **Enterprise Architecture Analysis**
    - Hexagonal Architecture validation
    - Domain-Driven Design (DDD) pattern detection
    - SOLID Principles compliance checking
    - Security vulnerability detection
    - Code quality metrics and thresholds
- **Usage Examples:**
  ```bash
  # Fast parallel analysis (default: 4 concurrent files)
  hex-ddd-analyzer analyze "src/**/*.ts"

  # Maximum performance (8 concurrent files)
  hex-ddd-analyzer analyze "src/**/*.ts" --max-concurrency 8

  # Sequential processing for debugging
  hex-ddd-analyzer analyze "src/**/*.ts" --disable-parallel
  ```
- **Front Matter (Russian):**
  - **Название документа:** Руководство пользователя Hexagonal DDD Analyzer
  - **Версия:** 1.0.0
  - **Дата:** 20 декабря 2025 года
- **Purpose:**
  - Validates codebase for:
    - SOLID principles
    - DDD patterns (entities, VOs, aggregates, services, repositories)
    - Hexagonal architecture (layers, dependency direction, ports & adapters, CQRS)
    - Security & quality (config management, sensitive data detection, complexity, naming conventions)
- **[→ Repository](https://github.com/bivex/tsPro)**

---

### [ideal-octo-engine](https://github.com/bivex/ideal-octo-engine)
- **Language:** PHP
- **Description:** PHP Quality Analyzer for SciTools Understand
- **[→ Repository](https://github.com/bivex/ideal-octo-engine)**

---

### [fluffy-memory](https://github.com/bivex/fluffy-memory)
- **Language:** Python
- **Description:** Pythonization of the brain for ISO/IEC/IEEE specifications — because even standards deserve clean syntax and fewer mental segfaults
- **[→ Repository](https://github.com/bivex/fluffy-memory)**

---

### [RedirectChecker](https://github.com/bivex/RedirectChecker)
- **Language:** Python
- **Description:** HTTP redirect checker
- **[→ Repository](https://github.com/bivex/RedirectChecker)**

---

### [EnvEditor](https://github.com/bivex/EnvEditor)
- **Language:** Python
- **Description:** Spying tool (environment variables)
- **[→ Repository](https://github.com/bivex/EnvEditor)**

---

### [ideal-waddle](https://github.com/bivex/ideal-waddle)
- **Language:** PHP
- **Description:** PHP Data Flow Analyzer
- **[→ Repository](https://github.com/bivex/ideal-waddle)**

---

## Summary

| Metric | Count |
|--------|-------|
| **Total Developer Tools** | 6 |
| **Languages** | TypeScript, PHP, Python |
| **Key Areas** | Static analysis, Quality tools, Utilities |

---

**[⬅️ Back to Inventory](../README.md)**
