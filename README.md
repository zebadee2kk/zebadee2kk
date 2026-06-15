# 💡 zebadee2kk — Richard Ham

**Expert Focus:** Fractional CISO · IT Director · AI Architect
**Core Value Proposition:** Helping SMEs, PE-backed, and high-growth businesses build secure, scalable technology without sacrificing delivery pace. Expertise at the intersection of cyber security, IT leadership, cloud modernization, and practical AI adoption.

---

## 🌐 Contact

| Channel | Link |
| :--- | :--- |
| **Website** | [richardham.co.uk](https://richardham.co.uk) |
| **LinkedIn** | [uk.linkedin.com/in/hamrichard](https://uk.linkedin.com/in/hamrichard) |
| **GitHub** | [github.com/zebadee2kk](https://github.com/zebadee2kk) |

---

## 🛠️ Core Areas of Expertise

### AI & Automation
- **Secure AI & Agentic Workflows:** Designing operating models with mandatory human approval gates, audit trails, cost control, and defined security boundaries.
- **AI Control Planes:** Building governed orchestration layers — deterministic substrate (systemd, scripts, CI) first; LLM orchestration (Hermes) above; frontier models (Perplexity, Claude Code, Codex) for research, build, and review.
- **Multi-Model Orchestration:** Routing work across local (LM Studio), cloud (OpenRouter), and specialist (Perplexity for research, Codex for review) providers based on task class and hardware constraints.

### Governance & Risk
- **Cyber Security & Compliance:** Cyber Essentials, ISO 27001, SOC 2, GDPR — practical readiness with demonstrable evidence, not shelfware.
- **Risk Management:** Transforming security from reactive tasks into owned programs with clear accountability and audit trails.
- **M&A Due Diligence:** Assessing technology estates, security posture, operational risk, and integration readiness.

### Cloud & Infrastructure
- **Modernization:** Microsoft 365, Azure, hosting, networking — secure, observable, maintainable.
- **Homelab & VPS:** Production-grade infrastructure management with NetBox-as-truth, Prometheus/Loki monitoring, and AI-assisted ops.

---

## 💻 Technical Build — Highlights (June 2026)

Recent concentrated work across the portfolio demonstrates the operating model in production:

### hermes-mgmt — AI Control Plane SSOT
- **15 parallel Claude Code sessions** deployed via git worktrees, each tackling a dedicated GitHub issue — all branches pushed and bulk-merged.
- **23 issues closed** across a single session: runtime config changes (fallback provider reordering, auxiliary vision pinning), security hardening (CVE-2026-48710 verified patched, gateway auth audited loopback-only), documentation refresh, and issue consolidation.
- **Observability stack deployed:** Langfuse v2 (port 3001), Langfuse v3 worker + ClickHouse + MinIO + Redis, Promptfoo (port 3002), PGAdmin — 9 containers, all smoke-tested.
- **Current-state documentation:** v0.16.0, 32 skills, fallback chain reordered, model/provider health verified.
- **Architecture defined:** Deterministic-substrate-first policy (ADR-0020), governed agent activation blueprint, 5-profile model (operator/research/builder/reviewer/ops).

### HAMNET — Infrastructure Lab
- 4 live systemd-based ops agents with deterministic evidence collection.
- NetBox as infrastructure source of truth, Prometheus/Loki monitoring.
- Repository canonicalized as the home and VPS infrastructure automation platform.

### New Repos (June 2026)
- `hermes-community-edition` — Fully free/nearly free Hermes deployment with local installers for Windows, Mac, Linux.
- `hamnet` — Public-facing HAMNET platform repo.
- `hermes-enterprise-reference-architecture` — Public reference companion for enterprise Hermes deployments.
- `client-agent-appliance` — Client-side agent deployment appliance.
- `AI-Alpha-Radar` — AI alpha news aggregator.
- `FlowFinder` — Agentic workflow finder from existing logs.

---

## 📦 Canonical Repository Map

| Repository | Role / Purpose | Visibility |
| :--- | :--- | :--- |
| `hermes-mgmt` | AI control plane SSOT — governance, runbooks, architecture, observability | Private |
| `hermes-community-edition` | Free Hermes deployment with local installers (Win/Mac/Linux) | Public |
| `hermes-enterprise-reference-architecture` | Enterprise reference companion for Hermes deployments | Public |
| `hamnet` | Home/VPS infrastructure lab — hosting, NetBox, monitoring, automation | Private |
| `HamOS` | Secure-by-design personal operating environment | Private |
| `agent-toolkit` | Reusable agent tooling, skills, templates, workflow components | Private |
| `portfolio-management` | GitHub estate governance, repo lifecycle, prioritization | Private |
| `control-tower` | GitHub-native control plane for AI-assisted project work | Public |
| `best-practice-repo-template` | Secure, maintainable repo template with governance standards | Public |
| `ai-powertools` | Workflow accelerators and AI-assisted development utilities | Public |
| `ai-cost-tracker` | Multi-model API cost tracking and budget visibility | Public |
| `client-agent-appliance` | Client-side agent deployment appliance | Private |
| `AI-Alpha-Radar` | AI alpha news aggregator | Private |
| `FlowFinder` | Agentic workflow finder from existing logs | Private |

---

## 🧭 Operating Principles

1. **Security first, delivery always** — Controls must reduce risk without stopping useful work.
2. **Human approval at critical gates** — Accountability remains explicit even with powerful automation.
3. **Deterministic substrate first** — Scripts, systemd, CI own execution; LLMs research, draft, review, route.
4. **Evidence over aspiration** — Governance leaves an auditable trail.
5. **Pragmatism over theatre** — Small, well-controlled changes over large, fragile programs.
6. **Git as SSOT** — All state changes committed before reporting.

---

## 🎯 Target Clients

- Organizations that have outgrown informal IT decision-making.
- Businesses under client/insurer security pressure.
- Companies adopting AI faster than their governance model safely supports.
- PE-backed and high-growth businesses needing fractional technology leadership.
