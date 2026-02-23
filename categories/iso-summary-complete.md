# 📐 ISO Standards SDKs - Complete Summary

> Complete catalog of ISO/IEC Go SDKs by @bivex
> Last updated: 2026-02-23

---

## Overview

This category contains Go SDKs implementing various ISO/IEC standards following Domain-Driven Design principles with clean architecture.

---

## ISO Standards Summary

| Project | Standard | Description | Stars | Updated |
|---------|----------|-------------|-------|----------|
| [iso13053](https://github.com/bivex/iso13053) | ISO 13053-2:2011 Six Sigma DMAIC | Complete implementation with 31 tools | 0 | 2026-01-04 |
| [iso22468](https://github.com/bivex/iso22468) | ISO 22468 - Value Stream Management | VSM Go SDK | 0 | 2025-12-09 |
| [iso25065](https://github.com/bivex/symmetrical-funicular-iso25065) | ISO 25065:2019 CIF for Usability | Common Industry Format Go SDK | 0 | 2025-12-09 |
| [iso8601-2](https://github.com/bivex/cuddly-journey-iso-8601-2-2019) | ISO 8601-2:2019 | Software Development Kit Go SDK | 0 | 2025-12-09 |
| [iso27031](https://github.com/bivex/silver-spoon-iso27031) | ISO/IEC 27031 | NTE INEN-ISO/IEC 27031 Go SDK | 0 | 2025-12-09 |
| [congenial-parakeet-iso9001](https://github.com/bivex/congenial-parakeet-iso9001) | ISO 9001:2015 Quality Management | Quality Management System Go SDK | 0 | 2025-12-30 |
| [iso38500](https://github.com/bivex/iso38500) | ISO 38500 - IT Governance | - | 0 | 2026-01-04 |
| [iso27031-alt](https://github.com/bivex/silver-spoon-iso27031) | ISO/IEC 27031 | NTE INEN-ISO/IEC 27031 Go SDK | 0 | 2025-12-09 |
| [iso8601-2-alt](https://github.com/bivex/cuddly-journey-iso-8601-2-2019) | ISO 8601-2:2019 | Software Development Kit Go SDK | 0 | 2025-12-09 |

---

## Detailed Project Descriptions

### [iso13053](https://github.com/bivex/iso13053) - ISO 13053-2:2011 Six Sigma

**Description:** Comprehensive Go SDK implementing ISO 13053-2 Six Sigma tools and techniques following Domain-Driven Design principles.

**Architecture:** Ports-and-Adapters (Hexagonal) pattern with strict layer separation

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

**Key Design Principles:**
- SOLID Principles — Strict adherence throughout codebase
- Clean Architecture — Dependencies point inward toward domain
- DDD Patterns — Ubiquitous language, bounded contexts, aggregates
- Hexagonal Architecture — Ports and adapters for infrastructure isolation
- CQRS-like Separation — Read and write models where beneficial
- Observability — Structured logging, metrics, and tracing built-in

**Project Structure:**
```
iso13053/
├── cmd/                    # Application entry points
├── internal/
│   ├── application/        # Use cases and application services
│   ├── domain/             # Domain layer (pure business logic)
│   ├── infrastructure/     # External concerns
│   └── presentation/      # CLI, HTTP, gRPC interfaces
├── pkg/                    # Public API
├── docs/                   # ADRs, examples
├── GLOSSARY.md             # Ubiquitous language
├── README.md
└── go.mod
```

**Features:**
- Complete implementation of Six Sigma DMAIC methodology
- All 31 tools and techniques from ISO 13053-2:2011
- Define, Measure, Analyze, Improve, Control phases

---

### [iso22468](https://github.com/bivex/iso22468) - ISO 22468 - Value Stream Management

**Description:** VSM Go SDK

**Standard:** ISO 22468 - Value Stream Management

**Purpose:** Provides tools and methodologies for managing value streams in organizations

---

### [symmetrical-funicular-iso25065](https://github.com/bivex/symmetrical-funicular-iso25065) - ISO 25065:2019

**Description:** ISO 25065:2019 Common Industry Format (CIF) for Usability Go SDK

**Standard:** ISO 25065:2019 - Common Industry Format for Usability

**Purpose:** Provides Go SDK for working with Common Industry Format (CIF) for usability specifications

---

### [cuddly-journey-iso-8601-2-2019](https://github.com/bivex/cuddly-journey-iso-8601-2-2019) - ISO 8601-2:2019

**Description:** ISO 8601-2:2019 Software Development Kit Go SDK

**Standard:** ISO 8601-2:2019 - Date/Time extensions for software development

**Purpose:** Provides comprehensive date and time handling capabilities following ISO 8601-2:2019 standard

---

### [silver-spoon-iso27031](https://github.com/bivex/silver-spoon-iso27031) - ISO/IEC 27031

**Description:** NTE INEN-ISO/IEC 27031 Go SDK

**Standard:** ISO/IEC 27031 - ICT readiness for business continuity

**Purpose:** Provides tools and methodologies for ICT readiness and business continuity planning

---

### [congenial-parakeet-iso9001](https://github.com/bivex/congenial-parakeet-iso9001) - ISO 9001:2015 Quality Management

**Description:** ISO 9001:2015 Quality Management System Go SDK

**Standard:** ISO 9001:2015 - Quality Management System

**Purpose:** Comprehensive QMS implementation following ISO 9001:2015 requirements

---

### [iso38500](https://github.com/bivex/iso38500) - ISO 38500 - IT Governance

**Description:** IT Governance framework implementation

**Standard:** ISO 38500 - IT Governance

**Purpose:** Provides framework for IT governance within organizations

**Note:** No README file available — repository may be a stub or template

---

## Common Architecture Pattern

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

## Standards Covered

| Standard ID | Name | Focus Area |
|-------------|------|-----------|
| ISO 13053-2 | Six Sigma DMAIC | Process improvement, statistical analysis |
| ISO 22468 | Value Stream Management | Process optimization, value streams |
| ISO 25065 | Common Industry Format | Usability engineering, CIF |
| ISO 8601-2 | Date/Time extensions | Software development date/time handling |
| ISO/IEC 27031 | ICT readiness | Business continuity, ICT preparedness |
| ISO 9001:2015 | Quality Management System | Quality assurance, processes |
| ISO 38500 | IT Governance | IT governance frameworks |
| ISO 9001:2015 | Quality Management System | QMS implementation |

---

## Summary

| Metric | Count |
|--------|-------|
| **Total ISO SDKs** | 8+ |
| **Languages** | Go |
| **Standards Covered** | IT Gov, Six Sigma, VSM, Usability, Date/Time, BC, QMS |
| **Architecture** | Hexagonal (Ports & Adapters) |
| **Design Patterns** | SOLID, DDD, CQRS, Clean Architecture |
| **Total Stars** | 0 |
| **With Detailed README** | 3+ (iso13053, iso22468, iso9001) |

---

## Commercial Potential

These SDKs provide enterprise-grade implementations of ISO standards:
- Custom development for enterprises seeking ISO compliance
- Consulting on ISO standard implementation
- White-label SDK licensing
- Training and certification support
- Audit preparation tools

---

**[⬅️ Back to Main ISO SDKs](./iso-sdks.md)**
