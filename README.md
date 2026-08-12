# Lukas Körber

Data Engineer & B.Sc. Applied AI student. I build data warehouses and ETL
pipelines by day, and self-hosted .NET apps on my own home k3s cluster by
night — from study tools to inventory management to push notifications.

Website: [lktec.org](https://lktec.org)

## Projects

- **[StudyLife](https://github.com/lukislp/studylife)** — self-hosted study organizer (Blazor WASM + ASP.NET Core): calendar, exam planner, focus timer, notes, progress dashboard. Also available as a [native MAUI app](https://github.com/lukislp/studylife-app) and a [Home Assistant integration](https://github.com/lukislp/studylife-hacs). **[Live demo →](https://studylife-demo.lktec.org)**
- **[studylife-ai](https://github.com/lukislp/studylife-ai)** — Python microservice extending StudyLife with an LLM agent: RAG study assistant over your own notes/courses/sessions with source citations, a LangGraph agent with a confirmation flow for write actions, and a RAGAS eval pipeline running in CI. FastAPI + LiteLLM (provider-agnostic — API models or fully local via Ollama) + Qdrant.
- **[Lagersystem](https://github.com/lukislp/Lagersystem)** — self-hosted inventory management system (Blazor Server): multi-warehouse, ML-powered anomaly detection, WebAuthn/passkeys, automated backups. Also available as a [Home Assistant integration](https://github.com/lukislp/Lagersystem-hacs).
- **[gitlab-monitor-hacs](https://github.com/lukislp/gitlab-monitor-hacs)** — Home Assistant integration for GitLab: pipelines, issues, merge requests, and releases as sensors per repository, for gitlab.com or self-hosted instances.
- **[HouseHoldPlanner](https://github.com/lukislp/HouseHoldPlanner)** — self-hosted household management app (Blazor WASM + ASP.NET Core): tasks, meal planning, recipes, calendars, shopping lists, and real-time chat.
- **[NotifyHub](https://github.com/lukislp/NotifyHub)** — universal .NET library for push notifications across browser (Web Push/VAPID), Apple (APNs), Android (FCM), webhooks, and email through a single channel-agnostic API.
- **[homelab-hub](https://github.com/lukislp/homelab-hub)** — self-hosted dashboard for homelab status monitoring. **[Live demo →](https://homelabhub-demo.lktec.org)**
- **[piwatch](https://github.com/lukislp/piwatch)** — real-time monitoring for Raspberry Pi k3s clusters. **[Live demo →](https://piwatch-demo.lktec.org)**
- **[UnifiProtectDashboard](https://github.com/lukislp/UnifiProtectDashboard)** — self-hosted dashboard for UniFi Protect cameras.
- **[ObdGarage](https://github.com/lukislp/ObdGarage)** — self-hosted, multi-user OBD2 vehicle tracker (Blazor Server + .NET MAUI): automatic trip log, maintenance planner, DTC diagnostics, fuel/cost tracking over a live ELM327 connection.

> **Licensing:** the primary self-hosted apps that manage real personal/business data (StudyLife, studylife-ai, Lagersystem, HouseHoldPlanner, ObdGarage) are **AGPL-3.0**, so any hosted fork has to share its changes back. Infrastructure tooling — dashboards, libraries, Home Assistant integrations — is **MIT**, since the point there is easy reuse and forking, not protecting a product.

## Stack

**Languages:** C# · TypeScript · JavaScript · Python · SQL

**Frameworks & Platforms:** .NET / ASP.NET Core · FastAPI · React · Kubernetes (k3s) · Docker

**AI & LLM:** LLM/RAG engineering · LangGraph agents · Vector search (Qdrant) · RAGAS evaluation · LiteLLM (provider-agnostic)

**Data:** Data warehousing · ETL pipelines · Oracle · Qlik Sense · ML integration

**Infrastructure & Other:** Home Assistant · IoT · CI/CD · AWS (Solutions Architect candidate)
