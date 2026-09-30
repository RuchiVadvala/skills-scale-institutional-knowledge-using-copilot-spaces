# OctoAcme Project Management Docs

Welcome to OctoAcme's project management guidance. This repository centralizes the playbooks, templates, and working norms we use to plan, deliver, track, and improve projects.

## Our project management approach

OctoAcme follows a structured, iterative delivery model built around five core principles:

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments to gather feedback early
- **Clear ownership**: Each project has a named Project Manager and Product Lead accountable for outcomes
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

The goal is to help teams move from idea to delivery with a common rhythm, shared artifacts, clear roles, and transparent communication.

## Project lifecycle

### 1. Initiation
Use this phase to validate the opportunity, align stakeholders, and decide whether to proceed.

- [octoacme-project-initiation.md](./octoacme-project-initiation.md)
- Define the problem, goals, success metrics, stakeholders, and first-pass plan
- Key deliverable: Project one-pager

### 2. Planning
Turn the approved initiative into a realistic backlog and delivery plan.

- [octoacme-project-planning.md](./octoacme-project-planning.md)
- Define scope, milestones, dependencies, acceptance criteria, and Definition of Done
- Key output: Prioritized backlog with estimates and release timeline

### 3. Execution & Tracking
Run the work with a consistent delivery rhythm and visibility into progress.

- [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md)
- Includes daily standups, sprint workflow, quality gates, and PR standards
- Key cadence: Daily standups, weekly delivery syncs, regular demos

### 4. Risk & Communication
Manage uncertainty and keep stakeholders informed throughout the project.

- [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md)
- Covers risk registers, stakeholder updates, communication templates, and escalation paths
- Key artifact: Risk register updated weekly

### 5. Release & Deployment
Standardize how features move to production safely and reliably.

- [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md)
- Includes pre-release checklists, deployment procedures, smoke testing, and rollback plans
- Key output: Release notes and deployment verification

### 6. Retrospective & Continuous Improvement
Capture what worked, what needs attention, and what to improve next cycle.

- [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md)
- Team reflection on execution and conversion of learnings to action items
- Cadence: After each sprint, release, or major milestone

## Cross-cutting reference docs

- [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) — High-level overview of principles, roles, artifacts, and lifecycle
- [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) — Role definitions, responsibilities, and communication patterns

## Quick reference

### Core roles & responsibilities
- **Project Manager (PM)**: Coordinates delivery, manages schedule, risks, communications, and dependencies
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, measures success, and validates solutions
- **Developers**: Implement features, maintain quality, participate in design and estimation
- **QA/Testing**: Validate acceptance criteria and quality standards
- **Stakeholders**: Provide input, alignment, and approval on key decisions

### Key artifacts
- Project one-pager / charter
- Roadmap and release plan
- Prioritized backlog with acceptance criteria
- Definition of Done
- Risk register
- Sprint / iteration backlog
- Retrospective notes and action items

### Communication cadence
- **Daily**: 15-minute team standups (focus on progress, blockers, dependencies)
- **Weekly**: PM + Product Manager sync
- **Twice-weekly**: Delivery team standups (or as agreed)
- **Monthly**: Stakeholder updates and reviews
- **Ad hoc**: Escalation when blockers or risks surface

### Quality standards
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed
- Small PRs (≤ 400 lines when possible) with clear acceptance criteria
- At least one approval before merging

## How to use this repository

1. **New to OctoAcme?** Start with [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) for a concise introduction.

2. **Starting a new project?** Follow the sequence: Initiation → Planning → Execution → Release → Retrospective.

3. **Managing day-to-day work?** Reference the [Execution & Tracking](./octoacme-execution-and-tracking.md) doc and the quick reference section above.

4. **Need role clarity?** See [Roles & Personas](./octoacme-roles-and-personas.md) for detailed responsibilities.

5. **Adding or updating processes?** Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.

Keep process docs updated as the team learns and improves its practice. Process improvement is built into our culture—use retrospectives to surface gaps and create issues to update guidance.
