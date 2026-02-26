# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, design, operations, business analysis, support, sales)
- Provide regular updates (weekly or milestone-based); Business Analyst prepares impact summaries for stakeholder reviews
- Use a single source of truth (project README or release doc) for status
- Support Lead provides post-launch customer feedback to PM/PdM within 48 hours of release

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level → PM → Engineering Lead / Product Lead → Sponsor
- Technical risks: Engineering Lead flags to PM; PM escalates to Sponsor if business impact is high
- UX/usability risks: UX Designer surfaces to PdM; PdM decides prioritization
- Operational/reliability risks: DevOps/SRE escalates to PM and Engineering Lead; follow incident runbook
- Business requirement risks: Business Analyst flags to PM and PdM with impact analysis
- Customer-impacting issues: Support Lead escalates to PM/PdM; QA triages with Engineering Lead
- For security incidents, follow the security incident runbook and notify Security on-call

## Escalation Checklist
When escalating an issue, ensure the following are documented before escalating:

- [ ] Clear description of the risk or blocker
- [ ] Estimated business or user impact (High/Med/Low)
- [ ] Roles involved and who owns the resolution
- [ ] Proposed mitigation or next steps
- [ ] Deadline or urgency level stated
- [ ] Relevant stakeholders notified (PM, Engineering Lead, Support Lead if customer-facing)
