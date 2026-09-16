# OctoAcme Project Management Processes

Welcome to OctoAcme's project management documentation. This folder contains comprehensive guides for running projects across our organization.

## Quick Start

OctoAcme follows a customer-first, iterative delivery approach with clear ownership and data-driven decisions. Our project lifecycle consists of five phases:

1. **Initiation** – Validate the problem, align stakeholders, and confirm go/no-go
2. **Planning** – Break work into shippable increments and establish success metrics
3. **Execution** – Build, test, review, and iterate with regular team rhythm
4. **Release** – Deploy to production with clear rollback and incident plans
5. **Close & Retrospective** – Capture learnings and drive continuous improvement

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Ship small, testable increments
- **Clear ownership**: Each project has named PM and Product Lead roles
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Overview of OctoAcme Project Management Processes

### Project Lifecycle & Workflows

OctoAcme follows a five-phase iterative delivery model designed to maximize customer value while maintaining clear ownership and accountability. The process begins with **Initiation**, where new ideas are validated through a lightweight Project One-pager that confirms business need, identifies stakeholders, and establishes success metrics. Once approved, teams move into **Planning**, where work is broken into prioritized backlog items with clear acceptance criteria, estimates, and dependencies. The **Execution** phase emphasizes a structured team rhythm—daily 15-minute standups, weekly delivery syncs, and demos at the end of each sprint—allowing teams to maintain momentum while surfacing blockers early. **Release & Deployment** is managed through standardized checklists and rollback plans to reduce production risk, followed by **Retrospectives & Continuous Improvement** where learnings are captured and converted into actionable improvements. This approach prioritizes iterative, shippable increments over big-bang releases, reducing risk and enabling faster feedback loops.

### Roles, Responsibilities & Communication

OctoAcme defines three core roles—**Project Manager** (coordinates delivery, manages schedules and risks), **Product Manager** (defines outcomes, prioritizes backlog, measures success), and **Developers** (implement features, collaborate on design)—with clear separation of concerns to prevent bottlenecks. Communication is structured yet flexible: weekly syncs between PM and Product Manager, twice-weekly team standups, monthly stakeholder updates, and ad-hoc escalations for critical issues. Risk management follows a three-level escalation path (team → PM → Product Lead → Sponsor), ensuring transparency without overwhelming leadership. A comprehensive Risk Register tracks all identified risks with impact, likelihood, mitigation plans, and owners, reviewed regularly during weekly syncs to catch emerging issues early.

### Quality Assurance & Execution Standards

OctoAcme enforces quality through multiple layers: unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI before any code reaches production. Pull requests are kept small (≤400 lines when possible) and require at least one approval plus passing automated tests before merging. The Definition of Done—documented during planning—ensures consistency in what "complete" means across the team. Teams use GitHub Projects for visual workflow management (Backlog → Ready → In Progress → In Review → QA → Done) and measure success through velocity, burndown, and key metrics identified in the Project One-pager. This combination of automated quality gates, manual verification, and data-driven metrics creates a feedback-rich environment where teams can confidently ship features while continuously improving processes and outcomes.

## Process Documentation

### Foundation & Overview
- [**Project Management Overview**](octoacme-project-management-overview.md) – Concise introduction to OctoAcme approach, roles, and key artifacts
- [**Roles and Personas**](octoacme-roles-and-personas.md) – Definitions of typical team roles and responsibilities

### Project Lifecycle
- [**Project Initiation**](octoacme-project-initiation.md) – Initial validation, stakeholder alignment, and go/no-go decision
- [**Project Planning**](octoacme-project-planning.md) – Breaking work into backlog, estimating, and establishing milestones
- [**Execution & Tracking**](octoacme-execution-and-tracking.md) – Day-to-day execution, team rhythm, and progress tracking
- [**Release & Deployment**](octoacme-release-and-deployment.md) – Standardized release process and deployment procedures
- [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) – Capturing learnings and driving improvements

### Cross-Cutting Concerns
- [**Risk Management & Communication**](octoacme-risks-and-communication.md) – Risk lifecycle, escalation, and stakeholder communication

## Communication Cadence

- **Weekly PM + Product Manager sync** – Align on priorities, dependencies, and risks
- **Twice-weekly team standups** (delivery team) – Daily progress, blockers, and help needed
- **Monthly stakeholder updates** – High-level status and milestone progress
- **Ad-hoc escalations** – For critical issues requiring immediate attention

## Getting Started

New team members should start with [**Project Management Overview**](octoacme-project-management-overview.md) for context, then dive into process docs based on your current project phase:

- **Starting a new project?** → Begin with [Project Initiation](octoacme-project-initiation.md)
- **Moving into execution?** → Read [Project Planning](octoacme-project-planning.md) and [Execution & Tracking](octoacme-execution-and-tracking.md)
- **Preparing to release?** → Review [Release & Deployment](octoacme-release-and-deployment.md)
- **Wrapping up a project?** → Review [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Key Artifacts

Across all phases of a project, OctoAcme teams maintain these core artifacts:

- **Project Charter / One-pager** – Problem statement, goals, success metrics, stakeholders
- **Roadmap and Release Plan** – High-level timeline and milestone structure
- **Sprint/Iteration Backlog** – Prioritized work with acceptance criteria and estimates
- **Definition of Done** – Shared understanding of what "complete" means
- **Risk Register** – Tracked risks with impact, likelihood, and mitigation plans
- **Retrospective notes and action items** – Learnings and improvements for the next cycle
