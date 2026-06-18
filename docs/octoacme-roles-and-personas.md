# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
---

## Additional Personas (proposed additions to improve clarity and accountability)

For each new persona below, add a short Role summary, Responsibilities, Goals / success criteria, and Typical communication & interactions.

### Technical Lead (Tech Lead)
- Role summary: Owns technical direction for a feature area and ensures technical quality and alignment with platform standards.
- Responsibilities:
  - Define high-level architecture and make technical trade-offs.
  - Create and review designs for non-trivial features.
  - Mentor developers and enforce code quality practices.
  - Coordinate cross-team technical dependencies.
- Goals / success criteria:
  - Low technical debt for the feature area.
  - Timely, well-scoped technical delivery that meets quality standards.
- Typical communication & interactions:
  - Works closely with Developers for implementation.
  - Partners with Product Manager on feasibility and technical constraints.
  - Syncs with Engineering Manager on staffing and risk.

### Engineering Manager (EM)
- Role summary: Manages people and team practices, ensuring healthy capacity and career growth.
- Responsibilities:
  - Capacity planning and resource allocation.
  - Performance coaching, hiring, and career development.
  - Resolve team-level impediments and blockers.
- Goals / success criteria:
  - Stable team capacity and predictable delivery.
  - Improved team health and retention metrics.
- Typical communication & interactions:
  - Coordinates with Project Manager on resourcing and timelines.
  - Works with Tech Leads on delivery risks and cross-team work.

### UX Researcher / Designer
- Role summary: Validates user needs, defines UX, and produces designs that meet usability and accessibility standards.
- Responsibilities:
  - Conduct user research and usability testing.
  - Produce design artifacts (wireframes, prototypes) and accessibility guidance.
  - Define usability-related acceptance criteria.
- Goals / success criteria:
  - High usability scores in testing and reduced user friction.
  - Design handoffs with clear specs for implementation.
- Typical communication & interactions:
  - Partners with Product Manager for requirements and prioritization.
  - Handoffs designs to Developers and participates in demos.

### Data / Insights Lead
- Role summary: Owns measurement strategy and ensures product changes are observable and measurable.
- Responsibilities:
  - Define success metrics and instrumentation needs.
  - Create dashboards and validate telemetry.
  - Lead post-release analysis and impact assessment.
- Goals / success criteria:
  - Reliable metrics and dashboards available for decisions.
  - Accurate measurement of feature impact.
- Typical communication & interactions:
  - Works with Product Manager on success metrics.
  - Collaborates with Developers to implement telemetry.
  - Supports QA for data validation.

### Site Reliability / Platform Engineer (SRE)
- Role summary: Ensures reliability, availability, and operability of services in production.
- Responsibilities:
  - Define and maintain SLOs and runbooks.
  - Improve observability and operational tooling.
  - Lead incident response for production issues.
- Goals / success criteria:
  - Meet defined reliability targets (SLOs).
  - Reduced mean time to detect/repair (MTTD/MTTR).
- Typical communication & interactions:
  - Collaborates with Developers to create runbooks and improve operability.
  - Works with Release Engineer on deployment safety and rollback plans.

### Release Engineer / Release Manager
- Role summary: Manages release pipelines and coordinates multi-team deployments.
- Responsibilities:
  - Maintain CI/CD pipelines and release processes.
  - Define release gating criteria and rollback plans.
  - Coordinate release schedules and communications.
- Goals / success criteria:
  - Smooth, predictable releases with clear rollback strategies.
  - Minimal production regressions introduced by releases.
- Typical communication & interactions:
  - Works with PM and SRE to schedule releases.
  - Coordinates with Developers to ensure PR readiness and cutover steps.
  - Notifies Support/Customer Success about release impacts.

### Business Analyst / PMO Liaison
- Role summary: Bridges business stakeholders and delivery teams to ensure clear, traceable requirements.
- Responsibilities:
  - Clarify requirements and maintain traceability between business goals and backlog items.
  - Prepare stakeholder reports and decision logs.
  - Assist in acceptance criteria definition for complex workflows.
- Goals / success criteria:
  - Reduced rework due to unclear requirements.
  - Up-to-date artifacts for stakeholders and audits.
- Typical communication & interactions:
  - Works with Product Manager and Project Manager on scope and reporting.
  - Prepares materials for stakeholder reviews and governance.

### Security Liaison
- Role summary: Ensures security considerations are integrated into design and delivery.
- Responsibilities:
  - Coordinate security reviews and threat modeling.
  - Run security scans and track remediation.
  - Escalate and document security risks.
- Goals / success criteria:
  - Reduced security findings and timely remediation.
  - Clear risk acceptance documented for residual issues.
- Typical communication & interactions:
  - Partners with Developers and Tech Leads during design/implementation.
  - Works with Product/PM on risk acceptance and mitigation plans.

### Customer Success / Support Liaison
- Role summary: Represents customer operational concerns and ensures releases are supportable.
- Responsibilities:
  - Provide customer feedback and operational context to prioritization.
  - Validate release readiness from a support perspective.
  - Create support playbooks and enablement content.
- Goals / success criteria:
  - Faster issue resolution and improved customer satisfaction.
  - Well-documented runbooks and support guides.
- Typical communication & interactions:
  - Informs Product and PM about recurring customer issues.
  - Collaborates with Release Engineer on communications and enablement.

### Accessibility Advocate
- Role summary: Ensures accessibility considerations are included across design and implementation.
- Responsibilities:
  - Review designs and implementations for accessibility issues.
  - Define accessibility acceptance criteria and testing steps.
  - Coordinate remediation and training where necessary.
- Goals / success criteria:
  - Conformance to chosen accessibility standards.
  - Fewer accessibility regressions in releases.
- Typical communication & interactions:
  - Works with UX, Developers, and QA to integrate accessibility into design, implementation, and testing.

---

## Suggested persona entry format (for contributors)
- Role name
  - Role summary
  - Responsibilities (bullet list)
  - Goals / success criteria
  - Typical communication & interactions (who they work with and how)

These additions should be short, actionable, and focused on who owns what and how that role engages with existing roles (PM, PdM, Developers, QA, Stakeholders).
