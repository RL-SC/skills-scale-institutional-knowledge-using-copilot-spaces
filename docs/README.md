# OctoAcme Project Management Docs

This README centralizes the OctoAcme project management process documents. It provides a comprehensive overview of our approach and direct links to the detailed docs in the `docs/` folder.

## Overview: OctoAcme Project Management Processes

OctoAcme operates a structured, customer-first project lifecycle designed to deliver value iteratively while maintaining clear ownership and accountability. Our approach is built on five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. 

**Initiation** validates business needs, aligns stakeholders, and creates a lightweight Project One-pager that defines the problem, goals, success metrics, and initial resource estimates. Once approved, the **Planning** phase breaks work into shippable increments, establishes acceptance criteria, estimates scope, and maps dependencies. This structured entry ensures all projects have clear success metrics and stakeholder alignment before development begins.

**Execution** and delivery are coordinated through defined team rhythms and governance structures. We use project boards (GitHub Projects) with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and a consistent Pull Request workflow that emphasizes small, reviewable changes (≤400 lines), automated CI/CD checks, and at least one approval before merge. Daily standups (15 minutes) surface progress and blockers, while weekly delivery syncs provide broader visibility into risk and dependencies. Quality is maintained through unit tests, integration tests, smoke tests for critical flows, and security scanning—backed by manual QA for feature acceptance when needed.

The project team structure is built on clear role separation: **Product Managers** define what should be built and measure outcomes; **Project Managers** coordinate delivery, manage risks and timelines, and maintain stakeholder communication; and **Developers** implement features while collaborating on design, testing, and risk mitigation. Communication cadence includes weekly PM-PdM syncs, twice-weekly standups for the delivery team, monthly stakeholder updates, and a three-level escalation path for blockers.

**Release & Deployment** follows a rigorous checklist that includes passing CI/security scans, staged deployment to testing environments, smoke tests, and post-deploy verification—backed by a documented rollback and incident playbook to minimize production risk. Finally, OctoAcme embeds continuous learning into every project cycle through structured **Retrospectives** held after each sprint or release, which capture learnings and translate feedback into tracked action items with clear owners and due dates.

---

## Documentation

- **[Project Management Overview](octoacme-project-management-overview.md)** — Concise introduction to roles, principles, lifecycle, and key artifacts used across all OctoAcme projects.

- **[Project Initiation Guide](octoacme-project-initiation.md)** — Initial steps to validate and authorize work, align stakeholders, and create a lightweight plan. Includes the Project One-pager template and decision gate.

- **[Project Planning](octoacme-project-planning.md)** — How to turn an approved initiative into an actionable plan and backlog for delivery. Covers backlog templates, sprint planning, risk management, and planning checklist.

- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution and tracking progress toward project milestones. Covers team rhythm, workflows, PR conventions, QA approach, and blocker escalation.

- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardizes how OctoAcme releases features to production to reduce risk and improve observability. Includes release types, pre-release checklists, and rollback playbooks.

- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — How to capture learnings and convert them into actionable improvements. Covers retrospective structure, tracking improvements, and building a continuous improvement culture.

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks and dependencies. Includes risk register format, stakeholder communication templates, and escalation paths.

- **[Roles & Personas](octoacme-roles-and-personas.md)** — Definitions of typical roles (Product Manager, Project Manager, Developer) and their responsibilities, used across all OctoAcme projects.

---

## How to Use

- **Onboarding:** Start here to understand OctoAcme's project management approach, then browse the linked docs for deeper detail.
- **Quick Reference:** Use this README to quickly find the right doc for your question or workflow phase.
- **Contributing:** To propose edits or add a new process doc, open an issue using the **"Add Content to Project Management Process Docs"** template (see `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`).

---

## Maintenance

- Keep links and document summaries updated when docs change.
- Review and refresh this README periodically to ensure it reflects current practices.
- Capture process improvements through retrospectives and update docs accordingly.
