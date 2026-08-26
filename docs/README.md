# OctoAcme Project Management Docs

## Welcome to OctoAcme's Project Management Processes

This folder contains the comprehensive project management framework used by OctoAcme teams to deliver projects consistently, transparently, and with focus on customer value.

## Our Approach

OctoAcme follows a structured yet flexible project management methodology built on these core principles:
- **Customer-First**: Prioritize customer value and usability in every decision
- **Iterative Delivery**: Ship small, testable increments rather than monolithic releases
- **Clear Ownership**: Every project has named owners (PM, Product Lead) with clear accountability
- **Data-Informed**: Make decisions based on metrics and evidence, not assumptions
- **Psychological Safety**: Foster an environment where team members feel safe to share feedback and learn

## OctoAcme Project Management Process Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer-first values, iterative delivery, and clear ownership. The organization operates on five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. Projects are governed by a lightweight governance model centered around a Project One-pager that captures the problem statement, measurable success metrics, stakeholders, and initial timeline. This gate-based approach ensures business alignment and measurable outcomes before committing significant resources. Key artifacts like the Project Charter, Risk Register, and Definition of Done provide transparency and traceability throughout the project lifecycle.

The delivery team is organized around clearly defined roles with distinct responsibilities. **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define priorities and success metrics; **Developers** implement features with quality and testability in mind; and **QA/Testing** ensures acceptance criteria and quality standards are met. This separation of concerns reduces ambiguity and enables focused accountability. Daily standups (15 min), weekly delivery syncs, and milestone demos create a regular rhythm of alignment and feedback. Cross-functional dependencies are tracked in a Risk Register and escalated through clear levels: team-level triage → PM to Product Lead → Sponsor escalation for business-impacting issues.

Execution follows disciplined practices designed to maintain quality and reduce risk. Work is managed on a project board with columns for Backlog, Ready, In Progress, In Review, QA, and Done, with pull requests kept small (≤400 lines when possible) and requiring at least one approval before merging. Automated testing, linting, and security scanning are embedded in CI pipelines before code reaches review. Feature acceptance combines automated testing with manual QA for critical flows, and team velocity and burndown metrics are tracked to inform planning. This quality-first approach extends through release, where smoke tests, rollback plans, and post-deploy verification minimize production risk.

Continuous improvement is institutionalized through retrospectives held after each sprint or milestone, where teams reflect on what went well and what could improve, translating insights into prioritized action items. Stakeholder communication is bidirectional and regular: weekly status updates follow a consistent template (progress, next steps, risks & blockers, decisions needed), and risk-based escalation ensures that production incidents and blocking issues are triaged and resolved with urgency. By centralizing these processes in versioned documentation and maintaining a single source of truth in the project repository, OctoAcme enables consistent execution, rapid onboarding, and institutional learning across teams.

## Project Lifecycle at a Glance

1. **Initiation** → Problem validation, stakeholder alignment, approval
2. **Planning** → Backlog creation, estimation, dependency mapping, release planning
3. **Execution** → Daily standups, iterative delivery, continuous testing
4. **Release** → Deployment, verification, stakeholder communication
5. **Retrospective** → Capture learnings, identify improvements, close out project

## Documentation Index

### Core Frameworks
- [**OctoAcme Project Management Overview**](octoacme-project-management-overview.md) — Start here to understand our approach, key roles, lifecycle, and artifacts
- [**Roles and Personas**](octoacme-roles-and-personas.md) — Detailed descriptions of Project Manager, Product Manager, Developer, and QA responsibilities

### Lifecycle Phases
- [**Project Initiation Guide**](octoacme-project-initiation.md) — How to validate ideas, align stakeholders, and decide go/no-go
- [**Project Planning**](octoacme-project-planning.md) — Breaking work into shippable increments, backlog creation, risk management
- [**Execution & Tracking**](octoacme-execution-and-tracking.md) — Day-to-day team rhythm, workflows, quality standards, metrics tracking
- [**Release & Deployment**](octoacme-release-and-deployment.md) — Pre-release requirements, deployment checklist, rollback procedures
- [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and converting them into action items

### Cross-Cutting Concerns
- [**Risk Management & Communication**](octoacme-risks-and-communication.md) — Risk identification, lifecycle, stakeholder communication, escalation paths

## How to Use These Docs

- **New to OctoAcme?** Read [OctoAcme Project Management Overview](octoacme-project-management-overview.md) first
- **Starting a new project?** Follow [Project Initiation Guide](octoacme-project-initiation.md)
- **Managing a project?** Refer to docs for your current lifecycle phase
- **Need to understand a role?** Check [Roles and Personas](octoacme-roles-and-personas.md)
- **Identifying risks?** See [Risk Management & Communication](octoacme-risks-and-communication.md)

## Key Artifacts You'll Encounter

- **Project Charter / One-pager** — High-level business case and success criteria
- **Risk Register** — Centralized tracking of risks, mitigation, and status
- **Sprint/Iteration Backlog** — Prioritized list of work with acceptance criteria
- **Definition of Done** — Team-agreed criteria for work completion
- **Release Notes** — Summary of changes, migration steps, known issues

## Need to Update These Docs?

Found a gap or want to add guidance? Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose updates.
