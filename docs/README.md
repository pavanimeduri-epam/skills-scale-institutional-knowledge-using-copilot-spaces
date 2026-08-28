# OctoAcme Project Management Processes

Quick overview
--------------
OctoAcme runs projects through a lightweight, stage-based lifecycle: Initiation to validate the problem and measurable outcomes; Planning to break approved work into a prioritized backlog and release plan; Execution to build, test, and deliver increments; Release to deploy with verification and rollback plans; and Retrospective to capture learnings and improvements. The approach emphasizes iterative delivery, clear ownership (named PM and Product Lead), data-informed decisions, and psychological safety for continuous learning.

Core workflows & quality practices
---------------------------------
- Initiation: produce a Project One-pager (problem, goals, success metrics, stakeholders, timeline) and confirm go/no-go before planning.
- Planning: run a kickoff, prioritize and estimate backlog items, define Definition of Done (DoD), and capture risks and dependencies in a simple Risk Register.
- Execution: use a project board with columns Backlog → Ready → In Progress → In Review → QA → Done. Follow a PR workflow that favors small pull requests, includes acceptance criteria and issue links, requires CI and at least one approval, and uses automated and manual testing as appropriate.
- Releases: require passing CI and security scans, prepared rollback plans, smoke tests in staging, and post-deploy verification. For incidents, follow the incident playbook and schedule blameless retrospectives.
- Continuous improvement: run timeboxed retrospectives, convert action items into backlog issues with owners and due dates, and track impact.

Navigation: core process documents
---------------------------------
- Project Management Overview — high-level framework and lifecycle  
  ./octoacme-project-management-overview.md

- Project Initiation — problem validation, one-pager, and decision gate  
  ./octoacme-project-initiation.md

- Project Planning — backlog, estimates, DoD, release plan, and risk register  
  ./octoacme-project-planning.md

- Execution & Tracking — team rhythm, project board, PR workflow, and blocker escalation  
  ./octoacme-execution-and-tracking.md

- Risk Management & Communication — risk register, stakeholder comms, and escalation paths  
  ./octoacme-risks-and-communication.md

- Release & Deployment — pre-release checks, deployment checklist, rollback playbook, and release notes template  
  ./octoacme-release-and-deployment.md

- Retrospective & Continuous Improvement — retrospective structure, action items, and follow-up  
  ./octoacme-retrospective-and-continuous-improvement.md

Reference: roles & personas
---------------------------
- Roles & Personas — definitions for Developers, Product Managers, Project Managers, QA/testing, and Stakeholders  
  ./octoacme-roles-and-personas.md

How to use this README
----------------------
- New team members: start with the Quick overview, then open the one-pager and Planning docs for the current project.
- Practitioners: follow the checklists in Execution & Tracking and Release & Deployment for daily and release readiness tasks.
- Process owners: update the relevant file in docs/ and use the existing ISSUE_TEMPLATE to request edits or additions.

Contact / Review
----------------
If anything here needs revision or additional links, please open an issue using the "Add Content to Project Management Process Docs" template or request an update in the project channel.
