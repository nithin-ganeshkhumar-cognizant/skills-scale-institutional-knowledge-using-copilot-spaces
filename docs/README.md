# OctoAcme Project Management Documentation

Welcome to OctoAcme's project management knowledge base. This documentation centralizes our proven processes, roles, and best practices to ensure consistent, efficient project delivery across all teams.

## Overview

### Our Approach
OctoAcme follows a lightweight, iterative project management framework grounded in five core principles:
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Every project has a named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Project Lifecycle at a Glance

```
Initiation → Planning → Execution → Release → Retrospective
```

## OctoAcme Project Management Overview

OctoAcme applies this lifecycle to all cross-functional projects that deliver product features, services, or integrations. The framework emphasizes:

- **Clear Roles & Ownership**: Each project has a named Project Manager (PM) coordinating delivery and a Product Manager (PdM) defining outcomes. Developers implement features, QA validates quality, and stakeholders provide approvals and inputs.

- **Key Artifacts**: Every project maintains a Project Charter/One-pager, Roadmap and Release Plan, Sprint/Iteration Backlog with acceptance criteria, Risk Register, and Retrospective notes.

- **Communication Cadence**: Weekly syncs between PM + PdM, twice-weekly standups for delivery teams, monthly stakeholder updates, and ad-hoc escalations as needed.

- **Quality & Testing**: Unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance.

- **Execution Tracking**: Use project boards (GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done. Small PRs (≤400 lines), automated testing/linting, and at least one approval before merging.

## Documentation Map

### Getting Started
- [**Project Management Overview**](octoacme-project-management-overview.md) — Start here to understand OctoAcme's principles, roles, and project lifecycle
- [**Roles and Personas**](octoacme-roles-and-personas.md) — Definitions of core roles (PM, PdM, Developers, QA) and their responsibilities

### Project Phases
1. **Initiation** → [Project Initiation Guide](octoacme-project-initiation.md)
   - Validate business need, identify stakeholders, define success criteria, decide go/no-go
2. **Planning** → [Project Planning](octoacme-project-planning.md)
   - Break work into shippable increments, identify dependencies, align timelines
3. **Execution** → [Execution & Tracking](octoacme-execution-and-tracking.md)
   - Day-to-day delivery, standups, quality assurance, blocker escalation
4. **Release** → [Release & Deployment Guide](octoacme-release-and-deployment.md)
   - Standardize releases, manage pre-release requirements, handle rollbacks
5. **Retrospective** → [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
   - Capture learnings, convert to action items, track improvements

### Cross-Cutting Topics
- [**Risk Management & Communication**](octoacme-risks-and-communication.md) — Identify, assess, and communicate risks; escalation paths; stakeholder updates

## How to Use These Docs

**New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md).

**Starting a new project?** Follow this sequence:
1. Read the [Project Initiation Guide](octoacme-project-initiation.md) to validate and authorize work
2. Move to [Project Planning](octoacme-project-planning.md) to create your backlog and timeline
3. Reference [Execution & Tracking](octoacme-execution-and-tracking.md) during delivery
4. Use [Release & Deployment](octoacme-release-and-deployment.md) when shipping to production
5. Wrap up with [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

**Managing risks or communications?** See [Risk Management & Communication](octoacme-risks-and-communication.md) at any phase.

**Need role clarity?** Refer to [Roles and Personas](octoacme-roles-and-personas.md) to understand responsibilities of PMs, Product Managers, Developers, and QA.

## Contributing & Feedback

To suggest updates or add new processes:
1. Create an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
2. Submit a pull request with your proposed changes
3. Ensure updates align with OctoAcme's core principles

### What We Value
- Clarity and accuracy in documentation
- Continuous refinement based on team feedback
- Alignment with core principles and proven practices
- Accessibility for all team members, especially new team members

---

*Last updated: 2026-09-15*
