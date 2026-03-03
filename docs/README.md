# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation. This README provides an overview of the processes, roles, and workflows used to deliver projects at OctoAcme, and links to all process documents in this folder.

## Overview

OctoAcme employs a lifecycle-based project management approach spanning **Initiation, Planning, Execution, Release, and Continuous Improvement**. Each project begins with a Project One-pager — a lightweight but comprehensive charter capturing the problem statement, SMART objectives, key stakeholders, success metrics, timeline, risks, and resource needs. Initiation is only approved when business value, stakeholder buy-in, and team availability are confirmed. Planning then breaks work into shippable increments with a prioritized backlog, effort estimates, explicit dependencies, a documented Definition of Done (DoD), and a living risk register — all aligned in a kickoff meeting before any development begins.

Execution is managed with a disciplined **GitHub Projects workflow**, moving work from Backlog → Ready → In Progress → In Review → QA → Done via small pull requests (≤400 lines where possible), automated CI checks, and acceptance criteria embedded in every PR description. Daily standups, weekly delivery syncs, and sprint demos enforce regular accountability, while blockers are escalated through a defined three-level protocol — from team triage to PM/Product Lead to executive sponsor. Quality assurance is embedded throughout with layered testing: unit, integration, and end-to-end smoke tests in CI, plus security scanning and manual QA sign-off for feature acceptance.

**Roles are precisely defined** to eliminate ambiguity: Product Managers own outcomes and backlog prioritization; Project Managers orchestrate delivery, schedules, and risk; Developers implement, test, and review; QA validates acceptance; and Stakeholders provide inputs and approvals. Communication is structured and templated — weekly PM–PdM syncs, twice-weekly standups, and monthly stakeholder updates are all standard cadences. Risks are tracked in a living Risk Register assessed by impact and likelihood, reviewed weekly, and escalated along a clear path: team-level → PM → Product Lead → Sponsor, with a dedicated security incident runbook for high-severity events.

Continuous improvement is a core cultural principle at OctoAcme. After every sprint, release, or incident, timeboxed **retrospectives** (45–75 min) surface what went well, what could improve, and produce 2–3 prioritized action items with owners and due dates — tracked in the project backlog and reviewed at the weekly PM sync. This loop — measuring the impact of improvements, celebrating wins, and making small iterative changes — reflects OctoAcme's broader principles: customer-first delivery, clear ownership, iterative releases, data-informed decisions, and psychological safety for the whole team.

## Docs Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

Each document details core workflows, roles, and templates to help the team execute reliably.
