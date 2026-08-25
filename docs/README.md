# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This folder contains comprehensive guides for running projects using the OctoAcme methodology—a customer-first, iterative approach to delivering product features, services, and integrations.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Management Overview

OctoAcme follows a structured, customer-centric lifecycle that emphasizes iterative delivery and clear ownership across all project phases. The approach spans five key stages: **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with defined acceptance criteria), **Execution** (daily standups and PR-based development), **Release** (standardized deployment with rollback procedures), and **Close & Retrospective** (capturing learnings for continuous improvement).

The organization operates with clearly defined roles—**Project Managers** coordinate schedules and risks, **Product Managers** define outcomes and prioritize the backlog, **Developers** implement features with high test coverage, and **QA/Testing** validates quality against acceptance criteria. Communication flows through a structured cadence: weekly syncs between PM and Product Manager, twice-weekly standups for delivery teams, and monthly stakeholder updates. Risk management is embedded throughout the process via a maintained Risk Register (tracking ID, description, impact, likelihood, owner, and mitigation), with escalation paths flowing from team-level triage → PM → Product Lead → Sponsor for business-impacting issues.

Quality and execution are ensured through rigorous PR workflows (small PRs ≤400 lines with automated CI/CD testing and linting), definition of done criteria, unit and integration testing, and end-to-end smoke tests before release. The team uses GitHub Projects for visualization with columns: Backlog → Ready → In Progress → In Review → QA → Done. Release management includes pre-release checklists, staging deployment verification, and documented rollback procedures. Finally, retrospectives held after sprints, releases, or milestones drive continuous improvement by capturing "what went well" and "what could improve," with action items tracked and reviewed in weekly PM syncs to ensure measurable impact and iterative refinement of processes.

## Process Documents

### Project Lifecycle

1. **[Project Initiation Guide](./octoacme-project-initiation.md)** — Validate business need, align stakeholders, and create lightweight plan
2. **[Project Planning](./octoacme-project-planning.md)** — Break work into shippable increments, identify dependencies, and establish timelines
3. **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day execution, team rhythm, and progress tracking
4. **[Release & Deployment](./octoacme-release-and-deployment.md)** — Standardize release processes and reduce deployment risk
5. **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert to actionable improvements

### Cross-Cutting Guidance

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to roles, artifacts, and communication cadence
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Definitions of typical project roles and responsibilities

## Quick Start by Phase

**Starting a new project?** → Begin with [Project Initiation Guide](./octoacme-project-initiation.md)

**Planning delivery?** → See [Project Planning](./octoacme-project-planning.md) and [Execution & Tracking](./octoacme-execution-and-tracking.md)

**Managing risks?** → Reference [Risk Management & Communication](./octoacme-risks-and-communication.md)

**Preparing for release?** → Follow [Release & Deployment](./octoacme-release-and-deployment.md)

**Improving your process?** → Use [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## Key Artifacts at a Glance

| Phase | Key Artifacts |
|-------|----------------|
| Initiation | Project One-pager, Stakeholder List, Risk List |
| Planning | Prioritized Backlog, Release Plan, Definition of Done |
| Execution | Sprint Backlog, PR Workflow, Risk Register (active) |
| Release | Release Notes, Smoke Tests, Rollback Plan |
| Retrospective | Action Items, Metrics Review, Continuous Improvement Log |

## Communication Cadence

- **Daily standups** (15 min) — Progress, blockers, dependencies
- **Weekly PM + PdM sync** — Alignment and planning
- **Twice-weekly team standups** — Delivery coordination (or as agreed)
- **Monthly stakeholder updates** — Status and metrics
- **Sprint demos/reviews** — Feature acceptance and feedback
- **Retrospectives** — After sprints, releases, or milestones

## How to Use These Docs

1. **Bookmark** this README as your navigation hub
2. **Reference** specific guides during your project phase
3. **Keep the Project Charter updated** in your project repo
4. **Contribute improvements** — These docs evolve with team feedback

---

**Questions or feedback?** Open an issue with the label `process improvement` or contact your Project Lead.
