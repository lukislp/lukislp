# Lukas Körber

Data Engineer & B.Sc. Applied AI student. I build data warehouses and ETL
pipelines by day, and self-hosted .NET apps on my own home k3s cluster by
night — from study tools to inventory management to push notifications.

Website: [lktec.org](https://lktec.org)

> **Note:** I've been building these projects since 2024 on my self-hosted GitLab instance (CI/CD included — it's part of my homelab). I migrated them to GitHub in August 2026, which is why the commit history and contribution graph here only start then.

## Projects

- **[StudyLife](https://github.com/lukislp/studylife)** — self-hosted study organizer (Blazor WASM + ASP.NET Core): calendar, exam planner, focus timer, notes, progress dashboard. Also available as a [native MAUI app](https://github.com/lukislp/studylife-app) and a [Home Assistant integration](https://github.com/lukislp/studylife-hacs). **[Live demo →](https://studylife-demo.lktec.org)**
- **[studylife-ai](https://github.com/lukislp/studylife-ai)** — Python microservice extending StudyLife with an LLM agent: RAG study assistant over your own notes/courses/sessions with source citations, a LangGraph agent with a confirmation flow for write actions, and a RAGAS eval pipeline running in CI. FastAPI + LiteLLM (provider-agnostic — API models or fully local via Ollama) + Qdrant.
- **[studylife-mcp](https://github.com/lukislp/studylife-mcp)** — Model Context Protocol server exposing StudyLife to Claude and other MCP clients: read tools for courses/notes/sessions/course goals, write tools for creating notes and sessions, and a self-built OAuth 2.1 authorization server for multi-user remote access. Python + the official MCP SDK.
- **[studylife-capture](https://github.com/lukislp/studylife-capture)** — Chrome extension (Manifest V3) for saving a selection or a whole article from any page into StudyLife as a note, auto-enriched by studylife-ai in the background: course matching scoped to active courses, tags, a summary, and related-notes suggestions. TypeScript + esbuild, Mozilla Readability for article extraction. **[Install →](https://chromewebstore.google.com/detail/studylife-capture/glhegeoapkifmhodpnbfjgijlflkdglh)**
- **[Lagersystem](https://github.com/lukislp/Lagersystem)** — self-hosted inventory management system (Blazor Server): multi-warehouse, ML-powered anomaly detection, WebAuthn/passkeys, automated backups. Also available as a [Home Assistant integration](https://github.com/lukislp/Lagersystem-hacs).
- **[gitlab-monitor-hacs](https://github.com/lukislp/gitlab-monitor-hacs)** — Home Assistant integration for GitLab: pipelines, issues, merge requests, and releases as sensors per repository, for gitlab.com or self-hosted instances.
- **[HouseHoldPlanner](https://github.com/lukislp/HouseHoldPlanner)** — self-hosted household management app (Blazor WASM + ASP.NET Core): tasks, meal planning, recipes, calendars, shopping lists, and real-time chat.
- **[NotifyHub](https://github.com/lukislp/NotifyHub)** — universal .NET library for push notifications across browser (Web Push/VAPID), Apple (APNs), Android (FCM), webhooks, and email through a single channel-agnostic API.
- **[homelab-hub](https://github.com/lukislp/homelab-hub)** — self-hosted dashboard for homelab status monitoring. **[Live demo →](https://homelabhub-demo.lktec.org)**
- **[piwatch](https://github.com/lukislp/piwatch)** — real-time monitoring for Raspberry Pi k3s clusters. **[Live demo →](https://piwatch-demo.lktec.org)**
- **[UnifiProtectDashboard](https://github.com/lukislp/UnifiProtectDashboard)** — self-hosted dashboard for UniFi Protect cameras.
- **[ObdGarage](https://github.com/lukislp/ObdGarage)** — self-hosted, multi-user OBD2 vehicle tracker (Blazor Server + .NET MAUI): automatic trip log, maintenance planner, DTC diagnostics, fuel/cost tracking over a live ELM327 connection.

> **Licensing:** the primary self-hosted apps that manage real personal/business data (StudyLife, studylife-ai, studylife-mcp, studylife-capture, Lagersystem, HouseHoldPlanner, ObdGarage) are **AGPL-3.0**, so any hosted fork has to share its changes back. Infrastructure tooling — dashboards, libraries, Home Assistant integrations — is **MIT**, since the point there is easy reuse and forking, not protecting a product.

## Stack

**Languages:** C# · TypeScript · JavaScript · Python · SQL

**Frameworks & Platforms:** .NET / ASP.NET Core · FastAPI · React · Kubernetes (k3s) · Docker · Chrome Extensions (Manifest V3)

**AI & LLM:** LLM/RAG engineering · LangGraph agents · Vector search (Qdrant) · RAGAS evaluation · LiteLLM (provider-agnostic) · MCP (Model Context Protocol)

**Data:** Data warehousing · ETL pipelines · Oracle · Qlik Sense · ML integration

**Infrastructure & Other:** Home Assistant · IoT · CI/CD · GitOps (Flux CD) · AWS (Solutions Architect candidate) · OAuth 2.1 (self-built authorization server)
