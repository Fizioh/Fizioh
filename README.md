<h1 align="center">Yassine Benosmane</h1>

<p align="center">
  <strong>Full-Stack & Geospatial Engineer · Agentic Systems Builder</strong><br/>
  Founder @ Khamseen Technologies
</p>

<p align="center">
  I build production systems at the intersection of <strong>software engineering</strong>,
  <strong>geospatial platforms</strong> and <strong>AI orchestration</strong>.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/benosmaneyassine">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://khamseen.tech">
    <img src="https://img.shields.io/badge/khamseen.tech-111827?style=flat-square&logo=google-chrome&logoColor=white" alt="Khamseen" />
  </a>
  <a href="https://bocus.ai">
    <img src="https://img.shields.io/badge/bocus.ai-111827?style=flat-square&logo=google-chrome&logoColor=white" alt="Bocus" />
  </a>
</p>

---

<p align="center">
  <img src="./assets/engineering-system-map.svg" width="100%" alt="Khamseen OS agent infrastructure map" />
</p>

## Engineering

- **Agent infrastructure** — control planes, runtime abstractions, skills, policy gates, audit trails and autonomous execution.
- **Geospatial platforms** — ArcGIS Experience Builder, ArcGIS Maps SDK for JavaScript, spatial workflows and API-driven GIS applications.
- **Full-stack systems** — TypeScript/React frontends, Python/Django backends, PostgreSQL, Redis and containerized infrastructure.
- **Reliability** — deterministic checks, explicit failure states, independent QA, bounded retries and observable execution.

## Current focus — Khamseen OS

> **Agent-native enterprise control plane** designed to coordinate humans, autonomous agents, deterministic systems, tools and replaceable execution runtimes.

Khamseen owns the semantics that should not disappear inside an LLM or a vendor runtime:

`Agent · Task · Run · Unit · Event · ToolCall · Decision · Gate · Approval · Audit`

The architecture deliberately separates the **control plane** from the execution plumbing. Khamseen keeps authority, policy and business state; interchangeable infrastructure can handle execution, isolation, tools and model access.

### Under the hood

**Graph ≠ Loop.** A graph decides which Units should exist, what actually depends on what, and what can run in parallel. A loop converges one Unit toward correctness:

`produce → check → correct → repeat → escalate`

**Capability ≠ Skill ≠ Tool.** Capabilities define what an agent is authorized to do. Skills encode the procedure for doing it. Tools are external actions. The Agent Skills layer is being designed around versioned `SKILL.md` contracts and progressive loading so agents receive procedural context only when it is needed.

**Runtime plumbing stays replaceable.** Execution flows through abstractions such as `RuntimeAssignment`, harnesses, sandboxes and gateways rather than binding agent identity to a model or vendor. **Hermes** is integrated behind the runtime boundary; **OpenClaw** is being evaluated through a bounded external-runtime adapter spike. Cursor, Codex, Claude Code and future providers can sit behind the same architectural contract.

**Deterministic before LLM.** Tests, type checks, schema validation, git diff/scope checks, dependency state, authorization and resource budgets should decide what they can before model judgment is used. Implementation and independent review remain separate execution contexts.

**Human authority stays explicit.** The objective is not “AI with no humans”; it is moving human involvement toward goals, exceptions and consequential approvals instead of manually babysitting every intermediate step.

## Stack

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/ArcGIS-2C7AC3?style=flat-square&logo=esri&logoColor=white" alt="ArcGIS" />
</p>

---

<p align="center">
  <sub>Building systems where agents can act autonomously without making authority, evidence or failure disappear.</sub>
</p>
