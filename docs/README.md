# OctoAcme Project Management Processes

## Overview

OctoAcme follows a structured, iterative approach to project management that emphasizes customer value, clear ownership, and data-informed decisions. This folder contains comprehensive guides for each phase of the project lifecycle, designed to help teams execute consistently and reduce onboarding time.

### Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Product and Project leads
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Key Approach Highlights

OctoAcme's project management processes emphasize a **lifecycle-based workflow** with five phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. Each project is governed by a **Project One-pager** that captures the problem statement, success metrics, and high-level timeline, ensuring alignment before work begins.

The framework defines four primary personas—**Project Managers** (who coordinate schedules, risks, and communications), **Product Managers** (who define what should be built and measure outcomes), **Developers** (who implement features with rigorous testing), and **Stakeholders** (who provide inputs and approvals). This clear role definition ensures accountability and smooth collaboration.

Execution follows an iterative approach using project boards with defined columns (Backlog, Ready, In Progress, In Review, QA, Done), supported by small pull requests (≤400 lines), automated CI/CD testing, and mandatory code reviews. Teams maintain a regular cadence with daily standups, weekly syncs, and end-of-sprint demos to track velocity and monitor risks. Quality assurance is embedded at every stage through unit tests, integration tests, security scanning, and manual QA validation.

Communication is structured around stakeholder groups with weekly status templates. A **Risk Register** tracks risks throughout the project lifecycle with escalation paths flowing from team-level triage to Product Lead to Sponsor. After each sprint or milestone, teams hold retrospectives to capture learnings and identify prioritized action items, creating a continuous improvement culture that refines processes over time.

## Project Lifecycle

1. **Initiation** - Validate need, align stakeholders, create high-level plan
2. **Planning** - Break into shippable increments, identify dependencies
3. **Execution** - Build, test, review, iterate
4. **Release** - Deploy and verify in production
5. **Close & Retrospective** - Capture learnings and continuous improvements

## Process Documentation

### Getting Started
- [Project Management Overview](./octoacme-project-management-overview.md) - High-level introduction to roles, artifacts, and lifecycle
- [Roles and Personas](./octoacme-roles-and-personas.md) - Definitions of core roles and responsibilities

### Phase-Specific Guides
- [Project Initiation Guide](./octoacme-project-initiation.md) - Validation, stakeholder alignment, go/no-go decisions
- [Project Planning](./octoacme-project-planning.md) - Backlog creation, estimation, dependencies, release planning
- [Execution & Tracking](./octoacme-execution-and-tracking.md) - Day-to-day execution, team rhythm, quality standards
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) - Release types, pre-release checklist, deployment and rollback

### Cross-Functional Practices
- [Risk Management & Communication](./octoacme-risks-and-communication.md) - Risk registers, escalation, stakeholder updates
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) - Post-sprint/release learning and action items

## How to Use These Docs

**For Developers**: Start with [Roles & Personas](./octoacme-roles-and-personas.md), then review [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md).

**For Product Managers**: Review [Project Management Overview](./octoacme-project-management-overview.md), then [Project Planning](./octoacme-project-planning.md), [Execution & Tracking](./octoacme-execution-and-tracking.md), and [Release & Deployment](./octoacme-release-and-deployment.md).

**For Project Managers**: Start with [Project Management Overview](./octoacme-project-management-overview.md), then review all phase-specific guides and [Risk Management & Communication](./octoacme-risks-and-communication.md).

**For New Team Members**: Begin with [Project Management Overview](./octoacme-project-management-overview.md) and [Roles & Personas](./octoacme-roles-and-personas.md), then explore phase-specific guides as needed for your role.

## Contributing

To update or add content to the process docs, please use the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).
