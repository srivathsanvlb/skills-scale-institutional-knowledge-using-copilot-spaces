# OctoAcme Project Management Process Documentation

Welcome to the OctoAcme project management documentation hub. This repository contains the comprehensive guides and processes used to manage, execute, and improve projects at OctoAcme.

## Quick Overview

OctoAcme follows a structured yet iterative approach to project management grounded in five key principles:
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named leadership and accountability
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and continuous learning

## OctoAcme Project Management Approach

OctoAcme operates on a structured lifecycle approach that emphasizes customer value, iterative delivery, and clear ownership. The organization applies a five-phase model—Initiation, Planning, Execution, Release, and Retrospective—to all cross-functional projects.

Three central roles anchor each project: the Project Manager (PM) coordinates delivery and schedules, the Product Manager defines outcomes and measures success, and the development team (Developers, QA/Testing, Stakeholders) executes and validates work. This role clarity ensures accountability while enabling collaboration across functional boundaries.

The planning phase transforms approved ideas into actionable work by breaking initiatives into shippable increments, establishing a prioritized backlog with clear acceptance criteria, and mapping dependencies and risks. Projects use GitHub Projects boards with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and enforce a lightweight pull request workflow with small PRs (≤400 lines), automated CI testing, and mandatory peer approval.

OctoAcme maintains a formal Risk Register that tracks identified risks and uses a tiered escalation model for communication. All project artifacts—charters, roadmaps, backlogs, and risk registers—are maintained in the project repository (in `.copilot/` for Copilot Spaces context), creating a single source of truth. Post-release and post-milestone retrospectives capture learnings and convert them into prioritized action items, reinforcing a culture of continuous improvement.

## Project Lifecycle

OctoAcme projects flow through five key stages:

1. **Initiation** - Define the problem, validate business need, align stakeholders
2. **Planning** - Break work into shippable increments, identify risks and dependencies
3. **Execution** - Build, test, review, and iterate with regular team rhythm
4. **Release** - Deploy to production with quality gates and rollback planning
5. **Close & Retrospective** - Capture learnings and drive continuous improvement

## Core Roles

Every OctoAcme project involves cross-functional teams with clear ownership:

- **Project Manager**: Coordinates delivery, manages schedules, risks, and communications
- **Product Manager**: Defines outcomes, prioritizes backlog, measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and strategic direction

For detailed role descriptions, see [OctoAcme Roles and Personas](octoacme-roles-and-personas.md).

## Process Documentation

### Starting a Project

- **[OctoAcme Project Management Overview](octoacme-project-management-overview.md)** - High-level introduction to OctoAcme's approach, principles, roles, and key artifacts
- **[OctoAcme Project Initiation Guide](octoacme-project-initiation.md)** - Steps to validate business need, align stakeholders, and create initial planning

### Planning & Setup

- **[OctoAcme Project Planning](octoacme-project-planning.md)** - How to break work into shippable increments, estimate scope, and create release plans

### Executing & Tracking Work

- **[OctoAcme Execution & Tracking](octoacme-execution-and-tracking.md)** - Day-to-day execution, team rhythm, quality standards, and blocker escalation

### Managing Risks & Stakeholders

- **[OctoAcme Risk Management & Communication](octoacme-risks-and-communication.md)** - Risk registers, lifecycle, stakeholder communication, and escalation paths

### Releasing & Deploying

- **[OctoAcme Release & Deployment Guide](octoacme-release-and-deployment.md)** - Release types, pre-release requirements, deployment checklist, and rollback procedures

### Learning & Improving

- **[OctoAcme Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** - How to capture learnings, drive improvements, and measure impact

## How to Use These Docs

1. **New to OctoAcme?** Start with [OctoAcme Project Management Overview](octoacme-project-management-overview.md) for a concise introduction.
2. **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md) docs.
3. **Currently executing?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and keep the [Risk Management & Communication](octoacme-risks-and-communication.md) guide handy.
4. **Ready to release?** Use the [Release & Deployment Guide](octoacme-release-and-deployment.md) for pre-release and deployment procedures.
5. **Closing out?** Run a retrospective using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).

## Communication Cadence

- Weekly sync between PM + Product Manager
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## Contributing & Feedback

These processes are living documents. If you have feedback, identified gaps, or want to propose improvements, please open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
