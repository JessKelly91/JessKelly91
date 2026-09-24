# Hi, I'm Jess 👋

Backend and platform engineer building production C#/.NET services on Azure Kubernetes Service, with Terraform and a GitOps release model behind them. I also engineer AI governance into systems, so controls get built and tested rather than only documented. I hold the IAPP AIGP certification and co-build a Responsible AI practice alongside my platform work.

I care about building systems that are both technically sound and thoughtfully designed. My background in English Literature and editorial work shapes how I approach documentation, communication, and the human side of technology.

---

## What I'm working on

- **Platform engineering** at Albany ITG — .NET API and gRPC services on AKS, Terraform, Argo CD, and GitOps release pipelines; reviewing and approving changes for two junior engineers
- **Responsible AI practice** — co-building Albany ITG's AI governance consulting practice and running NIST AI RMF assessments across GOVERN, MAP, MEASURE, and MANAGE
- **IntraMind** — my open-source testbed for agentic search and practical RAI tooling
- **Learning Dutch** (A1, actively studying) — relocating to the Netherlands 🇳🇱

## Recently

- ✅ Passed the **IAPP AIGP** certification (August 2026)
- ✅ Completed **Mila's TRAIL** Responsible AI programme (2026)
- 🚀 Shipped an LLM conformity report generator into internal use (July 2026)

---

## Tech stack

**Cloud & Infrastructure**
`Azure` `Azure Government` `AKS` `Kubernetes` `Helm` `Terraform` `Argo CD` `KEDA` `Azure Functions` `Azure Service Fabric` `Azure Container Registry` `Azure Key Vault`

**Languages & Backend**
`C#` `.NET` `Python` `TypeScript` `SQL` `PowerShell` `Bash` `gRPC` `REST APIs` `Microsoft Entra ID`

**CI/CD & DevOps**
`GitHub Actions` `Azure DevOps` `GitOps` `Docker` `BitBucket` `Jira`

**Data**
`SQL Server` `PostgreSQL` `Azure Data Factory` `Azure Blob Storage`

**Observability & Reliability**
`Prometheus` `Azure Monitor` `Application Insights` `OpenTelemetry`

**AI Engineering**
`LLM applications` `RAG` `Agentic retrieval` `Evaluation harness design` `PII redaction` `Output safety classification`

**AI Governance**
`NIST AI RMF` `ISO/IEC 42001` `EU AI Act` `Conformity assessment` `Control design & evidence` `Model monitoring & drift`

**Practices**
`Infrastructure as Code` `Zero-downtime deployments` `Code review` `TDD` `Agile` `Platform engineering`

---

## Featured projects

**AI Governance Conformity Report Generator** *(professional — source not public)*
Python LLM application that generates NIST AI RMF and ISO/IEC 42001 conformity reports from uploaded documentation and source repositories. In internal use since July 2026, replacing a manual process of 8+ hours per report.
- Every finding grounded in a cited source passage via RAG with agentic retrieval, as the primary control against fabricated findings
- Calibration harness scores output against a labelled ground-truth corpus on precision and recall, with locked thresholds gating release
- Zero tolerance for uncited critical findings; framework control content versioned under a governed changelog

---

**Release Management Redesign** *(professional — source not public)*
Rebuilt release management for a federal-sector product in Azure Government on an auditable GitOps model:
- ~300 pipeline definitions across five environments consolidated into 20 (93% reduction)
- Enforced separation between author and merger

---

**ServiceFabric → AKS Migration** *(professional — source not public)*
Led a full platform migration to Azure Kubernetes Service using GitOps practices, achieving:
- 60% reduction in node count
- Up to 38% per-pod memory reduction
- ~16% average reduction in container image size through AOT compilation and infrastructure optimisation

---

**[IntraMind](https://github.com/JessKelly91/IntraMind)** — AI-powered enterprise knowledge search platform
A microservices system for semantic search across internal documents, with a built-in Responsible AI stack — all running locally at $0 SaaS cost. Built to demonstrate both agentic AI architecture and practical RAI tooling.

*Stack:* `Python` `ASP.NET Core` `LangGraph` `LangChain` `gRPC` `Weaviate` `Docker` `GitHub Actions` `Preact`

*RAI tooling:* Phoenix (OTEL tracing) · Ragas (RAG evaluations in CI) · Microsoft Presidio (PII redaction) · Llama Guard (output safety) · Evidently AI (drift monitoring) · model & dataset cards

---

## Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jessica-k-kelly/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:JessKelly91@outlook.com)

---

*Backend and platform engineer with an AI governance specialty. Open to backend, platform, and cloud roles, as well as AI governance and responsible AI engineering positions. Relocating to the Netherlands; available for remote-first roles now.*
