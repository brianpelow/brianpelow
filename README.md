# Brian Pelow

**Live dashboard**: https://brianpelow.github.io

**Engineering leader** building at the intersection of platform engineering, agentic AI, and regulated industries.

I work on the hard problems in fintech, manufacturing, and regulated software where engineering excellence is not optional and the blast radius of getting it wrong is real. My open-source work reflects the kind of platform and tooling investments I have led and care about: developer productivity, operational reliability, compliance automation, and the agentic future of engineering operations.

---

## Portfolio

### Agentic systems

| Repo | What it does |
|------|-------------|
| [IncidentPilot](https://github.com/brianpelow/IncidentPilot) | Multi-agent incident response: triage, escalation, runbook retrieval, and post-mortem drafting with LangGraph |
| [DataPipelineAgent](https://github.com/brianpelow/DataPipelineAgent) | ETL orchestrator that monitors pipelines, detects schema drift, and auto-heals data quality issues |
| [BoardroomBrief](https://github.com/brianpelow/BoardroomBrief) | Autonomous weekly engineering brief: pulls GitHub, JIRA, and incident data into exec-ready narratives |

### MCP servers

| Repo | What it does |
|------|-------------|
| [mcp-incident-intel](https://github.com/brianpelow/mcp-incident-intel) | Wires PagerDuty, Dynatrace, and runbooks into a single incident context source for LLM agents |
| [mcp-compliance-grc](https://github.com/brianpelow/mcp-compliance-grc) | Maps SOC 2, ISO 27001, and PCI-DSS controls to code evidence and drafts compliance narratives |
| [mcp-developer-portal](https://github.com/brianpelow/mcp-developer-portal) | Wraps Backstage: lets AI agents query the service catalog, fetch TechDocs, and scaffold services |

### Engineering metrics

| Repo | What it does |
|------|-------------|
| [TeamHealthRadar](https://github.com/brianpelow/TeamHealthRadar) | DORA + SPACE framework scoring with AI-synthesized weekly health narratives |
| [PlatformSLOBoard](https://github.com/brianpelow/PlatformSLOBoard) | SLO aggregation from Dynatrace and PagerDuty with error budget tracking and exec summaries |
| [TechDebtLedger](https://github.com/brianpelow/TechDebtLedger) | Scans repos for complexity hotspots and stale dependencies, produces a prioritized payoff roadmap |

### Developer productivity CLIs

| Repo | What it does |
|------|-------------|
| [repoforge](https://github.com/brianpelow/repoforge) | AI-assisted repo scaffolding with 7 templates tuned for regulated industries |
| [pr-autopilot](https://github.com/brianpelow/pr-autopilot) | Generates PR descriptions, suggests reviewers, and applies labels from your diff |
| [runbook-gen](https://github.com/brianpelow/runbook-gen) | Auto-generates operational runbooks from code, alert definitions, and incident history |

### Platform engineering patterns

| Repo | What it does |
|------|-------------|
| [platform-maturity-model](https://github.com/brianpelow/platform-maturity-model) | 5-level maturity framework with automated evidence collection across 6 capability domains |
| [innersource-scorecard](https://github.com/brianpelow/innersource-scorecard) | Grades repos on discoverability, documentation, contribution friction, and adoption signals |
| [service-catalog-sync](https://github.com/brianpelow/service-catalog-sync) | Automated Backstage catalog hydration: scans repos and infers ownership and tech stack |

### Control plane and governance

| Repo | What it does |
|------|-------------|
| [orbit-platform](https://github.com/brianpelow/orbit-platform) | Production Services Control Plane: 6-stage governance framework for container, VM, and desktop image builds |
| [cab-automation](https://github.com/brianpelow/cab-automation) | Change Advisory Board automation: AI-generated CAB packages, risk scoring, and deployment gates |
| [fintech-platform-reference](https://github.com/brianpelow/fintech-platform-reference) | Reference architecture: ADRs, SLOs, runbooks, Backstage catalog, and PCI-DSS/SOX/FFIEC control mappings |

### Meta and orchestration

| Repo | What it does |
|------|-------------|
| [platform-conductor](https://github.com/brianpelow/platform-conductor) | Meta-orchestrator: monitors all nightly agents, opens failure issues, posts weekly Discussions summaries |
| [brianpelow.github.io](https://github.com/brianpelow/brianpelow.github.io) | Live engineering intelligence dashboard at brianpelow.github.io |
| [portfolio-assistant](https://github.com/brianpelow/portfolio-assistant) | Claude-powered portfolio chatbot at brianpelow.github.io/portfolio-assistant |

### Just for fun

| Repo | What it does |
|------|-------------|
| [vibe-check-cli](https://github.com/brianpelow/vibe-check-cli) | Analyzes the vibe of any GitHub repo and delivers a brutally honest vibe report |
| [code-roast](https://github.com/brianpelow/code-roast) | Paste any code and get it brutally but lovingly roasted by a senior engineer who has seen things |
| [sports-analytics-for-engineers](https://github.com/brianpelow/sports-analytics-for-engineers) | DORA metrics for sports teams: deployment frequency, change failure rate, and MTTR for your favorite team |

---

## How this portfolio is built

Every repo follows the same engineering standards I hold production systems to:

- **Real working code** - not toy examples. Each tool solves a genuine problem.
- **Test suites** - 428 passing tests across 25 repos. CI on every push.
- **Agentic automation** - every repo has a nightly GitHub Actions agent that does real work and commits results autonomously.
- **Regulated industry context** - fintech, manufacturing, and regulated software are first-class concerns throughout.
- **Professional structure** - CHANGELOG, CONTRIBUTING, LICENSE, CODEOWNERS, ADR directory, and PR templates on every repo.

---

## Industry focus

**Fintech / Banking** - PCI-DSS, SOX ITGC, FFIEC, ISO 20022
**Manufacturing** - IEC 62443, ISO 9001, ISO 27001
**Regulated SaaS** - SOC 2 Type II, continuous compliance, audit trail automation

---

## Technology

**Languages**: Python, TypeScript
**Agentic**: LangGraph, FastMCP, Anthropic Claude, OpenRouter
**Platform**: Backstage, GitHub Actions, Kubernetes, Terraform
**Observability**: Dynatrace, PagerDuty, Prometheus, Grafana
**Standards**: DORA, SPACE, SOC 2, ISO 27001, PCI-DSS

---

*All repos include autonomous nightly agents that commit real work. The activity graph is genuine.*