# OctoAcme Project Management Docs

This README provides a brief summary of OctoAcme's project management processes and direct links to the detailed process documents stored in the docs/ folder. Use this README as the single-entry index when onboarding new team members or when searching for process guidance.

## Quick summary

OctoAcme runs projects iteratively with clear ownership, a lightweight initiation step (one-pager & stakeholder alignment), regular planning and delivery rhythms, a focus on quality and testing, and explicit risk & communication practices. Key activities include project initiation, planning, execution, release & deployment, and retrospectives to capture improvements.

## Overview of Project Management Processes

OctoAcme uses an iterative, outcome-driven process oriented around small, verifiable increments:

- Initiation
  - Create a lightweight One-pager: problem, objective, success metrics, stakeholders.
  - Confirm sponsor and decide go/no-go for planning.

- Planning
  - Kickoff with stakeholders and delivery team.
  - Build a prioritized backlog with acceptance criteria and estimates.
  - Define the Definition of Done and a high-level release/milestone plan.
  - Identify dependencies and risks; add them to the Risk Register.

- Execution
  - Implement in small PRs with acceptance criteria linked to issues.
  - Run CI (tests, linting, security scans) before requesting reviews.
  - Team cadence: regular standups, weekly delivery syncs, demo/review at end of sprint.
  - QA: unit, integration, and smoke tests as appropriate.

- Release & Deployment
  - Follow pre-release checklist (passing CI, release notes, rollback plan).
  - Deploy to staging, run smoke tests, then to production via automated pipelines when possible.
  - Post-deploy verification and stakeholder communication.

- Continuous Improvement
  - Run retrospectives after sprints/releases/incidents.
  - Capture 2–3 actionable improvements and track them as issues with owners and due dates.
  - Review outstanding action items in weekly PM syncs.

## Process documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

> Note: This file lives in docs/, so links above are relative to the docs/ folder.

## How to use

- Keep this file at docs/README.md as the index for process docs.
- Link to it from the project README and onboarding materials.
- Update links and summaries when process documents change or new docs are added.

## Maintenance

- Each process doc owner should keep their file up to date.
- Consider adding this README to a quarterly docs review checklist to ensure accuracy.
