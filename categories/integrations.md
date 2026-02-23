# 🔗 Integrations

> Integration tools and connectors between platforms

---

## Featured Projects

### [GiteaPlaneBot](https://github.com/bivex/GiteaPlaneBot)
- **Language:** Python
- **Description:** PlaneBot — a bidirectional integration service that synchronizes tasks between Gitea and Plane project management platforms
- **Key Features:**
  - Bidirectional sync between Gitea and Plane
  - Webhook handling
  - Commit reference parsing
  - Project mapping
  - HMAC verification
  - REST API client
  - Task closure automation
  - Polling fallback
  - External ID mapping
- **Project Structure:**
  ```
  planebot/
  ├── app/                    # Main application
  │   ├── models/            # Data models
  │   ├── routers/           # API routes
  │   ├── services/          # Business logic
  │   └── utils/             # Utilities
  ├── config/                # Configuration files
  ├── docker/                # Docker files
  ├── docs/                  # Documentation
  ├── logs/                  # Logs and diagnostics
  ├── scripts/               # Scripts and utilities
  └── tests/                 # Tests
  ```
- **Documentation:**
  - [Main documentation](https://github.com/bivex/GiteaPlaneBot/docs/README.md)
  - [Integration guide](https://github.com/bivex/GiteaPlaneBot/docs/INTEGRATION_README.md)
  - [Deployment guide](https://github.com/bivex/GiteaPlaneBot/docs/DEPLOYMENT.md)
- **Development:**
  ```bash
  # Install dependencies
  pip install -r requirements.txt

  # Run tests
  python -m pytest tests/

  # Webhook diagnostics
  python scripts/diagnose_webhooks.py
  ```
- **Docker:**
  ```bash
  # Build and run
  docker-compose -f docker/docker-compose.yml up -d
  ```
- **Primary Keywords:** PlaneBot, Gitea integration, Plane integration, webhook synchronization, bidirectional sync, task automation
- **Technical Keywords:** API integration, webhook handler, commit parser, project mapping, HMAC verification, REST API client, FastAPI application
- **Integration Keywords:** Gitea webhook, Plane webhook, issue synchronization, commit reference, task closure, polling fallback, external ID mapping
- **[→ Repository](https://github.com/bivex/GiteaPlaneBot)**

---

### [PlaneCaldav](https://github.com/bivex/PlaneCaldav)
- **Language:** Python
- **Description:** Webhook for Plane Backend 4.2.16; Plane Frontend 0.23.1; Baïkal 0.10.1
- **Key Features:**
  - Plane webhook integration
  - CalDAV support via Baïkal
- **[→ Repository](https://github.com/bivex/PlaneCaldav)**

---

### [sendo](https://github.com/bivex/sendo)
- **Language:** JavaScript
- **Description:** A web application built with vanilla JavaScript for sending selected text from a website to a Telegram bot
- **[→ Repository](https://github.com/bivex/sendo)**

---

### [zeusus](https://github.com/bivex/zeusus)
- **Language:** JavaScript
- **Description:** Modding lighthouse
- **[→ Repository](https://github.com/bivex/zeusus)**

---

## Summary

| Metric | Count |
|--------|-------|
| **Total Integrations** | 4 |
| **Languages** | Python, JavaScript |
| **Key Areas** | Gitea, Plane, Telegram, Lighthouse |

---

**[⬅️ Back to Inventory](../README.md)**
