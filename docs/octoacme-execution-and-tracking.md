# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — developers, Engineering Lead, QA, DevOps/SRE; focus on progress, blockers, dependencies
- Weekly delivery sync — PM + PdM + Engineering Lead; show progress, updates, and flagged risks
- Bi-weekly design review — UX Designer, PdM, developers; align on wireframes and acceptance criteria
- Demo/Review at the end of each sprint or milestone (all delivery roles)
- Weekly support summary — Support Lead shares customer feedback and trends with PM/PdM

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup (developers, Engineering Lead, DevOps/SRE)
- Level 2: PM escalates to Product Lead, Engineering Lead, and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues (PM + Business Analyst prepare impact summary)
- Security/incident: DevOps/SRE leads triage; Support Lead notified for customer-facing impact

## Hand-off Checklist
Use this checklist when handing off work between roles (e.g., design → development, development → QA, QA → release):

- [ ] Acceptance criteria documented and agreed upon
- [ ] Design assets or specs shared with receiving team (UX Designer → Developers)
- [ ] Technical approach reviewed and approved by Engineering Lead
- [ ] Test cases written and reviewed by QA before development begins
- [ ] Deployment steps and rollback plan confirmed with DevOps/SRE before release
- [ ] Support Lead briefed on changes that may affect customers
- [ ] Business Analyst confirms requirements traceability and UAT sign-off

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
