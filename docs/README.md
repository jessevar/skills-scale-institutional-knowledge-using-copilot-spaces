# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management docs. This directory contains comprehensive guides on how we run projects, manage resources, and deliver value to our customers.

## Quick Start

- **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md)
- **Starting a new project?** Review [Project Initiation](octoacme-project-initiation.md)
- **Planning phase?** Check [Project Planning](octoacme-project-planning.md)
- **Managing your team?** See [Roles and Personas](octoacme-roles-and-personas.md)

## All Documentation

### Foundational
- [Project Management Overview](octoacme-project-management-overview.md) - High-level introduction to our approach, principles, and roles
- [Roles and Personas](octoacme-roles-and-personas.md) - Detailed role definitions and team member responsibilities

### Project Lifecycle
- [Project Initiation](octoacme-project-initiation.md) - Getting a project started
- [Project Planning](octoacme-project-planning.md) - Planning and scoping
- [Execution and Tracking](octoacme-execution-and-tracking.md) - Day-to-day delivery and monitoring
- [Release and Deployment](octoacme-release-and-deployment.md) - Going live and rollout
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) - Learning and iteration

### Cross-Cutting Concerns
- [Risks and Communication](octoacme-risks-and-communication.md) - Managing risks and team communication

---

## OctoAcme Project Management Processes Overview

OctoAcme follows a structured five-phase project lifecycle guided by customer-first principles, iterative delivery, clear ownership, data-informed decisions, and psychological safety. The organization is built around three core roles—Project Managers (who coordinate delivery and communications), Product Managers (who define outcomes and prioritize the backlog), and cross-functional delivery teams (developers and QA)—supported by stakeholders. Projects begin with an Initiation phase that establishes business need through a lightweight one-pager, identifies stakeholders, and gates the go/no-go decision. Once approved, teams move into Planning, where work is broken into shippable increments with clear acceptance criteria, dependencies are mapped, and a release timeline is established.

During the Execution phase, OctoAcme maintains a disciplined team rhythm with daily standups (15 minutes), weekly delivery syncs, and sprint-based iterations tracked on a GitHub Projects board. Quality is built into every step: developers write unit and integration tests, automated CI validates tests and linting, and manual QA assesses feature acceptance. Pull requests follow strict conventions (small PRs ≤ 400 lines, automated checks before review, one approval required), and teams use a structured escalation path for blockers—from daily standup triage to PM escalation to product leadership for business-critical issues.

Communication is strategic and multi-layered. Product and Project Managers sync weekly, delivery teams sync twice weekly, and stakeholders receive monthly updates via a centralized project README or release document. The organization maintains a risk register throughout each project, identifying, assessing, and monitoring risks with clear ownership and mitigation plans. For releases, OctoAcme follows a rigorous checklist including pre-release validation in staging, smoke tests before production deployment, and a documented rollback plan in case of incidents.

Finally, OctoAcme embeds continuous improvement into every project through structured retrospectives held after each sprint, release, or milestone. Retrospectives timebox to 45–75 minutes, focus on "what went well" and "what could improve," and surface 2–3 priority action items tracked back to the project backlog. This closed-loop approach—from initiation through retrospective—ensures that learnings compound over time and drive iterative refinement of both processes and team capabilities.

---

## Using These Docs

- Keep the Project Charter updated in your project repo
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context
- Link to relevant sections when discussing project decisions or processes with your team
- Use these as reference material during project initiation, planning, and retrospectives
