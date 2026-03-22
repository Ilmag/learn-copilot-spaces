# OctoAcme Project Management Processes

Welcome to OctoAcme's project management documentation. This guide serves as your entry point for understanding how we plan, execute, and continuously improve our projects. Whether you're a new team member getting up to speed or an experienced contributor looking for a quick reference, this README provides a structured overview of our approach and links to detailed process documents.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Project Lifecycle Overview](#project-lifecycle-overview)
3. [Core Roles & Responsibilities](#core-roles--responsibilities)
4. [Execution & Quality](#execution--quality)
5. [Communication & Continuous Improvement](#communication--continuous-improvement)
6. [Quick Links](#quick-links)

---

## Introduction

OctoAcme follows a **customer-first, iterative delivery** approach to project management. Our methodology is built on five core principles:

- **Customer-first** — Prioritize customer value and usability in every decision.
- **Iterative delivery** — Ship small, testable increments rather than large, infrequent releases.
- **Clear ownership** — Every project has a named Project Manager and Product Lead.
- **Data-informed decisions** — Measure impact and iterate based on evidence, not assumptions.
- **Psychological safety** — Encourage open feedback and treat mistakes as learning opportunities.

These processes apply to all cross-functional projects delivering product features, services, or integrations. The **Project Charter / One-pager** serves as the single source of truth for each project, capturing the problem statement, success metrics, timelines, and stakeholder list.

---

## Project Lifecycle Overview

OctoAcme projects move through five structured phases, each with clear goals, deliverables, and decision gates:

| Phase | Goal | Key Output |
|-------|------|------------|
| **1. Initiation** | Validate business need, align stakeholders, confirm go/no-go | Project One-pager, stakeholder list, high-level timeline |
| **2. Planning** | Break work into shippable increments, define scope and milestones | Prioritized backlog, release plan, Risk Register, Definition of Done |
| **3. Execution** | Build, test, review, and iterate toward milestones | Working software, sprint demos, updated risk register |
| **4. Release** | Deploy to production safely, verify, and announce | Release notes, post-deploy verification, stakeholder announcement |
| **5. Close & Retrospective** | Capture learnings and commit to improvement actions | Retrospective notes, action items with owners and due dates |

Each phase has a **decision gate** — for example, the team moves from Initiation to Planning only when success metrics are clear, stakeholders agree on priority, and team availability is confirmed.

---

## Core Roles & Responsibilities

OctoAcme projects are organized around three primary personas, with additional supporting roles:

### Project Manager (PM)
Coordinates delivery activities and keeps the project on track.
- Creates and maintains project plans, timelines, and the Risk Register
- Manages risks, dependencies, and resource constraints
- Facilitates meetings (kickoff, planning, retrospectives)
- Produces weekly status updates and stakeholder reports
- Escalates blockers through the defined escalation path

### Product Manager (PdM)
Defines *what* to build and *why* it matters.
- Defines problem statements and success metrics
- Prioritizes the roadmap and backlog
- Collaborates with engineering on trade-offs and technical feasibility
- Validates solutions through user research and outcome metrics

### Developers
Implement features and own code quality and reliability.
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Identify technical risks and propose mitigations

### Supporting Roles
- **QA / Testing** — Validate quality and acceptance criteria
- **Stakeholders** — Provide inputs, approvals, and strategic direction

> **Summary:** PM owns *how* and *when*. PdM owns *what* and *why*. Developers own *quality* and *feasibility*.

---

## Execution & Quality

### Daily Rhythm

| Cadence | Activity | Duration |
|---------|----------|----------|
| Daily | Standup — progress, blockers, dependencies | 15 min |
| Weekly | Delivery sync — metrics review, flagged risks, decisions | As needed |
| Per Sprint/Milestone | Demo / Review — showcase completed work | As agreed |

### Workflow Tracking

Work is tracked on a **GitHub Projects** board using the following columns:

**Backlog → Ready → In Progress → In Review → QA → Done**

Pull Request conventions:
- Keep PRs small (≤ 400 lines when possible)
- Include issue link and acceptance criteria in the PR description
- Run automated tests and linting in CI before requesting review
- Require at least one approval before merging

### Quality Gates

Every change must pass the following checks before release:
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows
- Security scanning in CI
- Manual QA sign-off for feature acceptance when needed

### Blocker Escalation Path

1. **Level 1** — Team-level triage in daily standup
2. **Level 2** — PM escalates to Product Lead and dependent teams
3. **Level 3** — Sponsor-level escalation for business-impacting issues

---

## Communication & Continuous Improvement

### Communication Cadence

| Audience | Frequency | Format |
|----------|-----------|--------|
| Delivery team | Daily | Standup |
| PM + PdM | Weekly | Alignment sync |
| Stakeholders | Weekly | Status update (progress, next steps, risks, asks) |
| Leadership / Executives | Monthly | Stakeholder briefing |

Status updates follow a standard template: **Progress this week → Next steps → Risks & blockers → Ask / decisions needed**.

### Retrospectives

After each sprint, release, or milestone, the team holds a structured retrospective (45–75 minutes):

1. **What went well** — Celebrate successes
2. **What could be improved** — Identify friction points
3. **Action items** — Commit to 2–3 prioritized improvements with clear owners and due dates
4. **Follow-up** — Review outstanding actions from previous retrospectives

Action items are added to the project backlog and reviewed in the weekly PM sync to ensure follow-through.

### Continuous Improvement Metrics

- **Velocity and burndown** — Track delivery pace over time
- **Success metrics** — Tied to the original Project One-pager goals
- **Observability dashboards** — Monitor errors, latency, and usage signals

---

## Quick Links

| Document | Description |
|----------|-------------|
| [Project Management Overview](./octoacme-project-management-overview.md) | Core principles, roles, artifacts, and lifecycle summary |
| [Project Initiation Guide](./octoacme-project-initiation.md) | How to validate and authorize new work |
| [Project Planning](./octoacme-project-planning.md) | Turning an approved initiative into an actionable plan |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day delivery rhythm, workflows, and quality practices |
| [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Standardized release process and deployment checklist |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Risk register, escalation paths, and communication templates |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Running retrospectives and tracking improvement actions |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Detailed role descriptions for PM, PdM, and Developers |

---

*For questions or suggestions about these processes, open an issue or start a discussion in this repository.*
