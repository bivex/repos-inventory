# 📐 ISO Standards SDKs

> Go SDKs implementing ISO/IEC standards with Domain-Driven Design

---

## Overview

Comprehensive Go SDKs for various ISO/IEC standards, following clean architecture and DDD principles.

---

## ISO SDK Projects

### [iso38500](https://github.com/bivex/iso38500)
- **Standard:** ISO 38500 - IT Governance
- **Language:** Go
- **Description:** IT Governance framework implementation
- **[→ Repository](https://github.com/bivex/iso38500)**

---

### [iso13053](https://github.com/bivex/iso13053)
- **Standard:** ISO 13053-2 - Six Sigma
- **Language:** Go
- **Description:** DMAIC methodology with 31 tools and techniques
- **Architecture:** Hexagonal (Ports & Adapters) pattern
- **Key Features:**
  - SOLID principles
  - Clean Architecture
  - DDD patterns (bounded contexts, aggregates)
  - Observability (logging, metrics, tracing)
- **[→ Repository](https://github.com/bivex/iso13053)**

---

### [iso22468](https://github.com/bivex/iso22468)
- **Standard:** ISO 22468 - Value Stream Management
- **Language:** Go
- **Description:** VSM Go SDK
- **[→ Repository](https://github.com/bivex/iso22468)**

---

### [iso25065](https://github.com/bivex/iso25065)
- **Standard:** ISO 25065 - CIF (Common Industry Format) for Usability
- **Language:** Go
- **Description:** Usability engineering Go SDK
- **[→ Repository](https://github.com/bivex/iso25065)**

---

### [iso8601-2](https://github.com/bivex/iso8601-2)
- **Standard:** ISO 8601-2 - Date/Time extensions
- **Language:** Go
- **Description:** Software Development Kit
- **[→ Repository](https://github.com/bivex/iso8601-2)**

---

### [iso27031](https://github.com/bivex/iso27031)
- **Standard:** ISO/IEC 27031 - ICT readiness for business continuity
- **Language:** Go
- **Description:** NTE INEN-ISO/IEC 27031 Go SDK
- **[→ Repository](https://github.com/bivex/iso27031)**

---

### [iso9001](https://github.com/bivex/congenial-parakeet-iso9001)
- **Standard:** ISO 9001:2015 - Quality Management System
- **Language:** Go
- **Description:** Quality Management System Go SDK
- **[→ Repository](https://github.com/bivex/congenial-parakeet-iso9001)**

---

## Architectural Principles

All ISO SDKs follow consistent architecture:

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
| **Languages** | Go |
| **Standards Covered** | IT Gov, Six Sigma, VSM, Usability, Date/Time, BC, QMS |

---

## Commercial Potential

These SDKs provide enterprise-grade implementations of ISO standards:
- Custom development for enterprises
- Consulting on ISO compliance
- White-label SDK licensing

---

**[⬅️ Back to Inventory](../README.md)**
