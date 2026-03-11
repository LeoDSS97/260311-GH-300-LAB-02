# OctoAcme Project Management Docs

This README serves as the central entry point and index to all OctoAcme process documentation. Use it to navigate key workflows, understand team responsibilities, and reference the standards that guide every phase of delivery.

---

## Summary of OctoAcme Project Management Processes

OctoAcme operates a structured, five-phase project lifecycle grounded in customer-first principles, iterative delivery, clear ownership, and data-informed decisions. The lifecycle spans **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective & Continuous Improvement**. During initiation, teams validate business need using a lightweight Project One-pager that defines the problem statement, objective (SMART-formatted), success metrics, stakeholder list, timeline/milestones, risks, and proposed team composition. The decision gate to move forward requires clear success metrics, stakeholder agreement on priority, and confirmed team availability. Once approved, planning breaks work into shippable increments with prioritized backlogs, acceptance criteria, Definition of Done, risk registers, and release timelines—creating a detailed blueprint before execution begins.

OctoAcme defines four core personas with explicit responsibilities: **Project Managers** coordinate delivery schedules, risks, dependencies, and cross-team communications; **Product Managers** define outcomes, prioritize the backlog, and measure success through data; **Developers** implement features while maintaining test coverage and quality standards; and **QA/Testing** validates acceptance criteria. This role clarity eliminates ambiguity and ensures accountability. Communication is tiered and consistent—daily standups (15 min) focus on blockers and dependencies, weekly delivery syncs show progress and flagged risks, weekly PM-to-PdM alignment sessions drive decisions, monthly stakeholder updates maintain transparency, and ad-hoc escalations address critical issues. Risk escalation follows a structured four-level path: team-level triage → PM escalation to Product Lead and dependent teams → sponsor-level escalation for business-impacting issues → security incident runbook for security-related risks.

During execution, teams leverage GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) to maintain real-time visibility. The pull request workflow emphasizes small PRs (≤400 lines), explicit issue linkage, acceptance criteria in descriptions, and automated CI checks (tests, linting, security scans) before requesting review. Quality is embedded throughout the workflow: unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, security scanning in CI pipelines, and manual QA for feature acceptance. Teams track velocity and burndown metrics while monitoring success metrics identified in the Project One-pager, creating a data-driven feedback loop. Blockers are escalated systematically, and dashboards surface key signals (errors, latency, usage).

Releases are de-risked through standardized pre-release requirements: all acceptance criteria met and PRs merged, passing CI and security scans, drafted release notes, and documented rollback/mitigation plans. OctoAcme distinguishes three release types—patch (hotfixes), minor (incremental features), and major (breaking changes)—each with its own deployment checklist covering staging verification, post-deploy verification, and stakeholder announcement. Retrospectives are held after each sprint, release, or milestone (timeboxed to 45–75 minutes) to capture what went well, identify improvements, and convert insights into action items with clear owners and due dates. This closing-the-loop discipline ensures OctoAcme continuously refines its processes, measures the impact of improvements, and maintains a culture of psychological safety for learning and feedback.

---

## Document Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level overview of OctoAcme's project management approach and guiding principles |
| [Project Initiation](octoacme-project-initiation.md) | Business need validation, Project One-pager template, and decision gate criteria |
| [Project Planning](octoacme-project-planning.md) | Backlog prioritization, acceptance criteria, Definition of Done, and release timelines |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | GitHub Projects workflow, PR standards, CI checks, and velocity/burndown tracking |
| [Risks and Communication](octoacme-risks-and-communication.md) | Risk register management, escalation paths, and communication cadences |
| [Release and Deployment](octoacme-release-and-deployment.md) | Pre-release requirements, release types, deployment checklists, and rollback plans |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Sprint/milestone retrospective format, action item ownership, and improvement tracking |
| [Roles and Personas](octoacme-roles-and-personas.md) | Responsibilities and expectations for Project Managers, Product Managers, Developers, and QA/Testing |
