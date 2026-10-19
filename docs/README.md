# OctoAcme Project Management Docs (README)

This README provides a central index of the OctoAcme project management process documentation and a short summary of the processes used across the project. It collects the key process documents stored in the docs/ folder and gives a quick reference for contributors and new team members.

## Summary of OctoAcme Project Management Processes

OctoAcme runs projects through a lightweight, iterative lifecycle that starts with a focused initiation phase and proceeds through planning, execution, release, and retrospective. Initiation centers on a Project One-pager that captures the problem, goals, success metrics, stakeholders, and a high-level timeline; the decision to move into planning requires clear success metrics and stakeholder alignment. Planning breaks approved initiatives into shippable increments with a prioritized backlog, estimates, a Definition of Done, and an explicit release plan and milestone map. Key artifacts — the one-pager, roadmap, backlog items with acceptance criteria, a risk register, and retrospective action items — serve as the single sources of truth for status and decisions.

Operational workflows emphasize predictable delivery and low-risk integration. Day-to-day work is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and executed with a small-PR pull request workflow that links issues, includes acceptance criteria, runs CI (tests and lint) before review, and requires approvals before merging. Planning and sprint ceremonies are timeboxed (kickoff, sprint planning, demos/reviews, retrospectives), and releases follow a documented checklist and rollback playbook; release types are classified (patch, minor, major) and require pre-release verification such as passing CI, security scans, smoke tests, and drafted release notes.

Roles and responsibilities are explicit: Product Managers define outcomes, prioritize the backlog, and own success metrics; Project Managers coordinate schedules, risks, communications, and ensure project artifacts are maintained; Developers implement features, write tests and docs, and participate in reviews; QA focuses on validation against acceptance criteria and test plans. Communication patterns tie roles together—regular cadences include daily standups, weekly delivery syncs, weekly PM+PdM alignment, and monthly stakeholder updates—while escalation paths (team → PM → Product Lead → Sponsor) and incident communication templates ensure clarity during problems.

Quality assurance and risk management are integrated into the flow. QA practices require unit and integration tests, end-to-end or smoke tests for critical flows, security scanning in CI, and manual QA when appropriate; CI gating is enforced prior to review and merge. A living risk register captures impact, likelihood, owner, and mitigation, and is reviewed regularly; reporting covers velocity, burndown, and dashboards for operational signals (errors, latency, usage). Retrospectives prioritize a few action items with owners and due dates so continuous improvement is tracked and fed back into the backlog and process docs.

## Docs Index

- [Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution and Tracking](docs/octoacme-execution-and-tracking.md)
- [Risks and Communication](docs/octoacme-risks-and-communication.md)
- [Release and Deployment](docs/octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](docs/octoacme-roles-and-personas.md)

## How to use this README

- Click the links above to open the detailed process documents.
- When adding new process content, open the appropriate document or propose a new one via the process doc update issue template in .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml.
- Keep this README updated when documents are renamed or new docs are added to docs/.

---

(If any doc filenames change or additional docs are added to docs/, update this README to keep the index current.)
