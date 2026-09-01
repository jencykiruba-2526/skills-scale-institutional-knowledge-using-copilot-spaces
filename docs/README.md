# OctoAcme Project Management Documentation

## Welcome to OctoAcme's Project Management Guides

This directory contains standardized process documentation for how OctoAcme runs projects. These guides help teams deliver customer value consistently, manage risks proactively, and capture learnings for continuous improvement.

## OctoAcme Project Management Principles

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments and gather feedback early
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

## Project Lifecycle Overview

OctoAcme projects follow a structured lifecycle:

1. **Initiation** → Validate business need, align stakeholders, confirm go/no-go
2. **Planning** → Define scope, create backlog, estimate effort, identify dependencies
3. **Execution** → Build, test, review, iterate with daily standups and demos
4. **Release** → Deploy to production with verification and stakeholder communication
5. **Retrospective** → Capture learnings and convert to actionable improvements

## OctoAcme Project Management Overview

OctoAcme operates on a customer-first, iterative delivery model grounded in five core principles: customer value prioritization, incremental release cycles, clear ownership structures, data-informed decision-making, and psychological safety. The project lifecycle follows a structured five-phase approach: **Initiation** (validating business need and stakeholder alignment through a Project One-pager), **Planning** (breaking work into shippable increments with defined acceptance criteria), **Execution** (daily standups and iterative delivery with automated testing), **Release** (standardized deployment with pre-release validation and rollback plans), and **Close & Retrospective** (capturing learnings and continuous improvement).

OctoAcme defines clear accountability through three primary roles: **Project Managers** coordinate delivery activities, manage schedules, risks, and stakeholder communications; **Product Managers** define what to build, prioritize the backlog, and measure outcomes through success metrics; and **Developers** implement features, write tests, and collaborate on design and quality. The communication cadence reinforces alignment—weekly syncs between PM and PdM, twice-weekly delivery standups, and monthly stakeholder updates keep all parties informed. Risk escalation follows a tiered path (team-level → PM → Product Lead → Sponsor), ensuring blockers are surfaced early and resolved at the appropriate level.

Day-to-day execution revolves around a project board (GitHub Projects) using columns for Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests follow strict conventions—small PRs (≤400 lines), linked to issues, and requiring at least one approval before merge. Quality assurance is embedded throughout: unit and integration tests for new logic, end-to-end smoke tests before release, security scanning in CI, and manual QA for feature acceptance when needed. Weekly demos and regular risk register reviews keep the team and stakeholders aligned on progress and emerging issues. Metrics—velocity, burndown, and product-specific success indicators—provide data-driven visibility into project health and enable informed decision-making at every stage.

## Documentation Hub

### Core Reference

- **[OctoAcme Project Management Overview](octoacme-project-management-overview.md)** — Start here for an introduction to roles, artifacts, and communication cadence
- **[OctoAcme Roles and Personas](octoacme-roles-and-personas.md)** — Understand responsibilities of Project Managers, Product Managers, Developers, and QA teams

### By Project Phase

**Initiation Phase**
- **[OctoAcme Project Initiation Guide](octoacme-project-initiation.md)** — Define problem, identify stakeholders, create a one-pager, and confirm go/no-go decision

**Planning Phase**
- **[OctoAcme Project Planning](octoacme-project-planning.md)** — Break work into shippable increments, estimate, define DoD, and create a release plan
- **[OctoAcme Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify risks, manage dependencies, and communicate status to stakeholders

**Execution Phase**
- **[OctoAcme Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day delivery, conduct standups, run demos, and track progress

**Release Phase**
- **[OctoAcme Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize releases, manage deployments, and prepare rollback plans

**Retrospective & Continuous Improvement**
- **[OctoAcme Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Run retrospectives, capture learnings, and drive team improvements

## Quick Start: Choosing the Right Doc

| Scenario | Document to Use |
|----------|-----------------|
| Starting a new project? | [Project Initiation Guide](octoacme-project-initiation.md) → [Project Overview](octoacme-project-management-overview.md) |
| Need to plan a project? | [Project Planning](octoacme-project-planning.md) |
| Managing daily execution? | [Execution & Tracking](octoacme-execution-and-tracking.md) |
| Identifying or managing risks? | [Risk Management & Communication](octoacme-risks-and-communication.md) |
| Preparing for release? | [Release & Deployment Guide](octoacme-release-and-deployment.md) |
| Improving your process? | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) |
| Understanding roles? | [Roles and Personas](octoacme-roles-and-personas.md) |

## Key Artifacts Referenced Across Docs

- **Project One-pager** — Captures problem, goal, success metrics, stakeholders, and risks
- **Project Backlog** — Prioritized list of work items with acceptance criteria
- **Risk Register** — Tracks identified risks, impact, likelihood, and mitigation plans
- **Definition of Done (DoD)** — Team-agreed standards for when work is complete
- **Release Notes** — Communicates changes, migration steps, and known issues
- **Retrospective Action Items** — Improvements identified and tracked with owners and due dates

## Using These Docs in Copilot Spaces

If you're using these docs as context in a Copilot Space, add this `docs/` directory to your Copilot Space knowledge base. This enables Copilot to provide:

- Guidance aligned with OctoAcme processes
- Suggested checklists and templates
- Project phase-specific recommendations

For more on scaling institutional knowledge, see the [project skills exercise](../README.md).
