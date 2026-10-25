# Awesome-Enterprise-Workflow-Automation-Integration

## Top Enterprise Workflow Automation & Integration Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Self-Hosted Visual Builders, AI-Enhanced Workflows & Data-Sovereign Orchestration*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Workflow Automation & Integration**. These tools connect apps, automate multi-step business processes, and orchestrate data flows across systems — with a spectrum running from polished commercial iPaaS suites to self-hosted platforms that keep workflow logic and credentials on your own infrastructure.

**Examples** include n8n, Activepieces, Huginn, Windmill, Node-RED, and Apache Airflow (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, permissive licensing, and AI-enhanced automation — especially relevant as **n8n** remains the technical team's choice with 400+ integrations and native AI capabilities [citation:1], while **Activepieces** offers a truly MIT-licensed alternative with 700+ integrations and a cleaner onboarding experience [citation:3].

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **Zapier** — **The reference commercial automation standard.** Connects 7,000+ apps with multi-step Zaps and AI-powered workflows. **Free tier: 100 tasks/month; paid from $19.99/month** [citation:3]. **Trade-offs**: per-task pricing scales steeply with volume, and no self-hosting option. **Best for teams** wanting the largest integration catalog without infrastructure management.

- **Make** — **The visual automation platform with published pricing.** Canvas-based scenario builder with routers, error handling, and 2,000+ connectors. **Free tier: 1,000 credits/month; Core at $12/month, Pro at $21/month** [citation:11]. **Best for visual builders** wanting more structural flexibility than linear trigger-action tools at a lower entry price than Zapier.

- **Workato** — **The enterprise iPaaS standard.** Recipe-based builder with 1,200+ connectors, governance controls, and Agent Studio for AI workflows. **Pricing via sales; self-service Pro starts at $75/month for 2,500 credits** [citation:2]. **Best for large IT-led programs** where business and technical teams share a governed automation library.

- **Microsoft Power Automate** — **The Microsoft 365 automation hub.** Deep integration with Office, Dynamics, and Azure with desktop RPA capabilities. **Premium at $15/user/month; unattended RPA at $150/bot/month** [citation:15]. **Best for Microsoft-centric organizations** where identity and licensing are already in place.

- **MuleSoft Anypoint** — **The API-led integration standard.** Comprehensive iPaaS with API management, governance, and enterprise connectors. **$2,000/month minimum billed annually** [citation:9]. **Best for enterprises** needing API governance and security controls as primary requirements.

## Open-Source GitHub Projects

- **n8n** — **The technical team's automation platform with native AI capabilities.** **Sustainable Use License** (source-available, not OSI-approved), self-hostable with **400+ integrations** and **AI nodes** for LLM calls, vector search, and agent workflows [citation:1]. **Free self-hosted with unlimited workflows and executions** [citation:1]. **Execution-based pricing is more predictable than per-step or per-user models** [citation:1]. **The honest caveat**: **steep learning curve for non-technical users**, and **documentation quality can be inconsistent** [citation:1]. **Best for engineering teams** wanting a self-hostable platform with deep AI integration and complex multi-step workflow support.

- **Activepieces** — **The truly MIT-licensed Zapier alternative.** **MIT licensed** — full commercial use and modification permitted, self-hostable via Docker [citation:1][citation:3]. **700+ integrations** with **60% built by users** [citation:1][citation:3]. **AI Agent support** and **280+ pieces exposed as MCP servers** for Claude/Cursor [citation:3]. **Free self-hosted with unlimited task execution**; cloud from $16/month [citation:9]. **The honest caveat**: **fewer integrations (500-700) than Zapier (7,000+)**, smaller community, and newer platform with potential stability concerns for mission-critical workflows [citation:1]. **Best for teams** wanting a permissive license with a cleaner, more approachable interface than n8n, accepting a smaller ecosystem.

- **Huginn** — **The fully free automation agent system.** **MIT licensed**, self-hosted, with **unlimited chaining, dynamic routing, and native scripting** — no paid tiers for webhooks, code steps, or multi-step logic [citation:13]. **WebsiteAgent can scrape sites, crawl APIs, and run JSONPath queries** with Liquid templating [citation:13]. **The honest caveat**: **you own the entire stack** — updates, security patches, Docker images, and backups are your responsibility [citation:13]. **Best for power users** wanting maximum control and unlimited automation without per-task pricing, accepting operational overhead.

- **Windmill** — **The developer-first scripting platform.** **AGPLv3 licensed**, treats scripts (TypeScript, Python, Go) as the unit of work and builds flows around them [citation:5][citation:15]. **AI agent step** can use your scripts as tools, with an MCP server exposing flows to AI assistants [citation:15]. **Free self-hosted with unlimited executions**; Enterprise from $120/month for SSO and audit logs [citation:15]. **The honest caveat**: **non-engineers will not build here** — it requires coding skills [citation:15]. **Best for engineering teams** whose workflows are primarily code rather than visual node graphs.

- **Node-RED** — **The event-driven IoT and hardware integration standard.** **Apache 2.0 licensed**, under the OpenJS Foundation, with a large community and no vendor pricing [citation:5][citation:15]. **Flow-based visual editor** for wiring devices, APIs, and services. **The honest caveat**: **no built-in SSO, access control, or audit trail** — you build those or add them via third-party support [citation:15]. **Best for IoT, event routing, and workloads close to hardware**, not general business system integration.

- **Apache Airflow** — **The data engineer's orchestration default.** **Apache 2.0 licensed**, battle-tested with a large provider ecosystem for integrations [citation:5]. **Workflows defined as Python DAGs** with scheduling and monitoring. **The honest caveat**: **built for scheduled data pipelines, not general business automation** — RBAC is coarse enough that hard team boundaries often mean separate deployments [citation:5]. **Best for data pipeline orchestration** where the work is scheduled batch processing rather than event-driven app integration.

### Additional Strong Open-Source Options

- **Camunda 8** — **The BPMN workflow standard.** Self-managed components under a source-available license with paid production use [citation:5]. Best for organizations needing BPMN modeling and human task orchestration alongside system integration.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Enterprise workflow automation tools differ significantly in licensing, integration depth, and operational requirements. **n8n's Sustainable Use License is source-available, not OSI-approved** — reselling as a hosted service is prohibited [citation:5]. **Activepieces is MIT-licensed** with the most permissive terms for commercial use [citation:1]. **The hidden cost of self-hosting** is engineering time: maintaining Docker containers, managing databases, applying security patches, and debugging outages can exceed SaaS subscription savings for lean teams [citation:4]. **Huginn requires you to own the entire stack** — updates and backups are your responsibility [citation:13]. **The choice often comes down to team skills and volume**: Activepieces for permissive licensing and approachability, n8n for AI-enhanced technical workflows, Huginn for unlimited automation without per-task fees, and Windmill for code-first engineering teams.
- Self-hosted open-source solutions require proper infrastructure (Docker, PostgreSQL, Redis for most platforms), and awareness that "free" self-hosted still has maintenance and DevOps costs.

---

**Made for operations teams, automation engineers, and organizations choosing enterprise workflow platforms that match their licensing needs, technical skills, and data-sovereignty requirements.**
Let's make enterprise workflow automation and integration more open, AI-enhanced, and developer-friendly.
