# OctoAcme Project Management Process Docs

This README collects the OctoAcme project management process documents and provides a short summary of each. Use these documents to understand how OctoAcme manages projects and to guide your own project execution.

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured, lifecycle-based approach to project management centered on five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. The process prioritizes customer value, iterative delivery, clear ownership, and data-driven decisions.

**During Initiation**, the team validates business need and creates a lightweight Project One-pager that captures the problem statement, success metrics, stakeholders, and initial timeline—moving to planning only when success criteria are clear and stakeholders are aligned. In the **Planning phase**, work is broken into shippable increments with prioritized backlogs, defined acceptance criteria, and a release plan that identifies dependencies and risks.

**Execution** emphasizes daily standups, weekly delivery syncs, and a pull request workflow with automated testing and security scanning, supported by GitHub Projects boards that track work through Backlog → Ready → In Progress → In Review → QA → Done columns. The team maintains a Risk Register throughout, escalating blockers through three levels (team triage, PM escalation, sponsor escalation) and measuring progress through velocity, burndown, and key dashboards.

Quality is assured through unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance. The team follows a pull request workflow requiring small PRs (≤400 lines when possible) with issue links and acceptance criteria, at least one approval before merge, and passing automated tests and linting. **Release** includes pre-release checklists, deployment verification, and rollback playbooks. A formal **Retrospective and Continuous Improvement** process captures learnings after each sprint, release, or milestone and converts them into actionable improvements with clear owners and timelines.

The organizational model relies on three primary personas working in close collaboration: **Project Managers** coordinate delivery and manage schedules and risks; **Product Managers** own the product vision and prioritize the backlog; and **Developers** implement features, write tests, and identify technical risks. All roles emphasize clear communication and shared accountability for project success, with communication cadence including twice-weekly standups, weekly PM + PdM syncs, monthly stakeholder updates, and demo/reviews at sprint or milestone end.

## Process Documents

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level principles, core roles, key artifacts, and lifecycle overview.
- **[Project Initiation Guide](octoacme-project-initiation.md)** — One-pager template, stakeholder alignment, and initiation checklist.
- **[Project Planning](octoacme-project-planning.md)** — Backlog templates, planning activities, risk capture, and planning checklist.
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Team rhythm, PR workflow, CI standards, quality practices, and execution checklist.
- **[Risks & Communication](octoacme-risks-and-communication.md)** — Risk register format, communication templates, and escalation paths.
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Release types, deployment checklist, rollback playbook, and release notes template.
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Retrospective structure, tracking improvements, and building continuous improvement culture.
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Role descriptions, responsibilities, and typical communication patterns.

## How to Contribute

To suggest updates or add new content to the process documentation:

1. Open an issue using the **"Add Content to Project Management Process Docs"** template (available in `.github/ISSUE_TEMPLATE/`)
2. Reference the document you want to modify or indicate if this is a new document
3. Include a summary of the proposed update, rationale, and suggested content
4. Link your pull request to the issue

Questions or feedback? Reach out to your Project Manager or Product Manager.
