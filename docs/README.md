# OctoAcme Project Management Docs

This README provides a comprehensive entry point for OctoAcme's project management processes and direct links to the full process documents stored in the docs/ folder.

---

## OctoAcme Project Management Overview

OctoAcme follows a structured, lifecycle-based project management approach centered on customer value delivery and clear ownership. The organization operates projects through five key phases: **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with defined acceptance criteria), **Execution** (day-to-day delivery with regular syncs and quality gates), **Release** (standardized deployment with pre-flight checks and rollback plans), and **Close & Retrospective** (capturing learnings for continuous improvement). This phased approach is supported by lightweight but consistent artifacts—including a Project One-pager, prioritized backlog, risk register, and release notes—which serve as single sources of truth and enable transparency across distributed teams.

### Core Roles & Responsibilities

Core to OctoAcme's success is a clear role structure with defined responsibilities:

- **Project Managers** coordinate schedules, risks, and communications
- **Product Managers** define outcomes and prioritize the backlog
- **Developers** implement features and collaborate on quality
- **QA/Testing** validates acceptance criteria and quality standards

This distributed ownership model is reinforced by a regular communication cadence: daily standups focus on progress and blockers, weekly syncs between PM and Product Manager align strategy, and ad-hoc escalations surface critical issues.

### Quality & Execution Practices

Quality and execution rigor are embedded throughout OctoAcme's workflows. During planning, teams define acceptance criteria and a Definition of Done. During execution, pull requests are kept small (≤400 lines), automated tests and linting run in CI before review, and a blocker escalation framework ensures issues are surfaced quickly. Risk management and stakeholder communication happen in parallel—risks are identified, assessed, and monitored in a shared register, while status updates follow standardized templates.

Pre-release gates require passing CI, security scans, and smoke tests, with documented rollback plans to minimize production risk. This combination of clear processes, distributed accountability, and quality-first practices enables OctoAcme teams to deliver iteratively while maintaining stakeholder confidence and psychological safety.

---

## Process Documents

Below are direct links to all OctoAcme project management process documents:

- **[octoacme-project-management-overview.md](./octoacme-project-management-overview.md)** — Overview, principles, core roles, key artifacts, and lifecycle
- **[octoacme-project-initiation.md](./octoacme-project-initiation.md)** — One-pager template, initiation checklist, and decision gate criteria
- **[octoacme-project-planning.md](./octoacme-project-planning.md)** — Backlog planning, sprint activities, risk & dependency management, and planning checklist
- **[octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md)** — Team rhythm, workflows, QA practices, reporting, blocker escalation, and execution checklist
- **[octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md)** — Risk register, risk lifecycle, stakeholder communication templates, and escalation paths
- **[octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md)** — Release types, pre-release requirements, deployment checklist, and rollback playbook
- **[octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md)** — Retrospective structure, action item tracking, and continuous improvement culture
- **[octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md)** — Detailed role summaries and responsibilities for Developers, Product Managers, and Project Managers

---

## How to Use These Docs

- **For new team members**: Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand OctoAcme's principles and lifecycle, then reference the specific phase documents as you work on projects.
- **During project phases**: Use the corresponding process document (e.g., use [Initiation](./octoacme-project-initiation.md) at project start, [Planning](./octoacme-project-planning.md) during scope definition, etc.).
- **For Copilot Spaces**: Add process-specific docs to your `.copilot/` directory to ground Copilot in OctoAcme's processes and get context-specific guidance.
- **For continuous improvement**: Propose updates via the [Process Doc Update issue template](./.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to keep these docs current and aligned with team practice.

---

## Key Artifacts Used Across Projects

- **Project Charter / One-pager** — Defines problem, goal, success metrics, and stakeholders
- **Roadmap and Release Plan** — High-level timeline and release schedule
- **Sprint/Iteration Backlog** — Prioritized, estimated work with acceptance criteria
- **Risk Register** — Tracked risks with mitigation plans and owners
- **Retrospective notes and action items** — Learnings and improvements from each phase or sprint

---

## Questions or Feedback?

If you have questions about OctoAcme's processes or wish to propose improvements, please:
1. Check the relevant process document for clarity
2. Reach out to your Project Manager or Product Manager
3. Open a [Process Doc Update issue](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to suggest enhancements or additions
