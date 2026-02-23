# 📐 ISO Standards SDKs

> Go SDKs implementing ISO/IEC standards with Domain-Driven Design principles

---

## Featured ISO SDKs

### [iso13053](https://github.com/bivex/iso13053)
- **Standard:** ISO 13053-2:2011 — Six Sigma
- **Language:** Go
- **Description:** Comprehensive Go SDK implementing ISO 13053-2 Six Sigma tools and techniques following Domain-Driven Design principles
- **Architecture:** Ports-and-Adapters (Hexagonal) pattern with strict layer separation
- **Key Design Principles:**
  - **SOLID Principles** — Strict adherence throughout codebase
  - **Clean Architecture** — Dependencies point inward toward domain
  - **DDD Patterns** — Ubiquitous language, bounded contexts, aggregates
  - **Hexagonal Architecture** — Ports and adapters for infrastructure isolation
  - **CQRS-like Separation** — Read and write models where beneficial
  - **Observability** — Structured logging, metrics, and tracing built-in
- **Project Structure:**
  ```
  iso13053/
  ├── cmd/                    # Application entry points
  ├── internal/
  │   ├── application/        # Use cases, DTOs, App Services
  │   ├── domain/             # Entities, VOs, Aggregates, Services, Events
  │   ├── infrastructure/     # Repositories, Adapters, External Services
  │   └── presentation/      # CLI, HTTP API, Events
  ├── pkg/                    # Public API
  ├── docs/                   # ADRs, examples
  ├── GLOSSARY.md             # Ubiquitous language
  ├── README.md
  └── go.mod
  ```
- **Features:**
  - Complete implementation of Six Sigma DMAIC methodology
  - All 31 tools and techniques from ISO 13053-2:2011
  - Define, Measure, Analyze, Improve, Control phases
- **[→ Repository](https://github.com/bivex/iso13053)**

---

## Other ISO SDKs

### [iso38500](https://github.com/bivex/iso38500)
- **Standard:** ISO 38500 — IT Governance
- **Language:** Go
- **Description:** IT Governance framework implementation
- **[→ Repository](https://github.com/bivex/iso38500)**

---

### [iso22468](https://github.com/bivex/iso22468)
- **Standard:** ISO 22468 — Value Stream Management
- **Language:** Go
- **Description:** VSM Go SDK
- **[→ Repository](https://github.com/bivex/iso22468)**

---

### [iso25065](https://github.com/bivex/iso25065)
- **Standard:** ISO 25065 — CIF (Common Industry Format) for Usability
- **Language:** Go
- **Description:** Usability engineering Go SDK
- **[→ Repository](https://github.com/bivex/iso25065)**

---

### [iso8601-2](https://github.com/bivex/iso8601-2)
- **Standard:** ISO 8601-2 — Date/Time extensions
- **Language:** Go
- **Description:** Software Development Kit
- **[→ Repository](https://github.com/bivex/iso8601-2)**

---

### [iso27031](https://github.com/bivex/iso27031)
- **Standard:** ISO/IEC 27031 — ICT readiness for business continuity
- **Language:** Go
- **Description:** NTE INEN-ISO/IEC 27031 Go SDK
- **[→ Repository](https://github.com/bivex/iso27031)**

---

### [iso9001](https://github.com/bivex/congenial-parakeet-iso9001)
- **Standard:** ISO 9001:2015 — Quality Management System
- **Language:** Go
- **Description:** Quality Management System Go SDK
- **[→ Repository](https://github.com/bivex/congenial-parakeet-iso9001)**

---

## Architectural Pattern

All ISO SDKs follow consistent hexagonal architecture:

```
┌─────────────────────────────────────────────────────────┐
│                    Presentation Layer                    │
│              (CLI, HTTP API, Events)                    │
└─────────────────────────────────────────────────────────┘
                          ↓
┌─────────────────────────────────────────────────────────┐
│                   Application Layer                     │
│            (Use Cases, DTOs, App Services)             │
└─────────────────────────────────────────────────────────┘
                          ↓
┌─────────────────────────────────────────────────────────┐
│                     Domain Layer                        │
│  (Entities, VOs, Aggregates, Domain Services, Events) │
└─────────────────────────────────────────────────────────┘
                          ↓
┌─────────────────────────────────────────────────────────┐
│                Infrastructure Layer                     │
│       (Repositories, Adapters, External Services)       │
└─────────────────────────────────────────────────────────┘
```

---

## Summary

| Metric | Count |
|--------|-------|
| **Total ISO SDKs** | 7 |
| **Language** | Go |
| **Standards Covered** | IT Gov, Six Sigma, VSM, Usability, Date/Time, BC, QMS |
| **Architecture** | Hexagonal (Ports & Adapters) |
| **Design Patterns** | SOLID, DDD, CQRS, Clean Architecture |

---

## Commercial Potential

These SDKs provide enterprise-grade implementations of ISO standards:
- Custom development for enterprises seeking ISO compliance
- Consulting on ISO standard implementation
- White-label SDK licensing
- Training and certification support

---

**[⬅️ Back to Inventory](../README.md)**
