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
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

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

Use the [Risk Escalation Template](templates/risk-escalation-template.md) for weekly status updates and escalations.

### Three-Level Escalation Contact Pattern

**Level 1: Team-Level Triage**
- Contact: Development team, QA, immediate team leads
- Response time: Same day
- Use for: Technical blockers, dependency issues, minor scope questions

**Level 2: Program Management**
- Contact: Project Manager → Product Manager → Product Lead
- Response time: Within 24 hours  
- Use for: Cross-team dependencies, resource constraints, timeline risks, scope changes

**Level 3: Executive Sponsor**
- Contact: Product Lead → Sponsor / Senior Leadership
- Response time: Within 4 hours for critical issues
- Use for: Budget approval, organizational blockers, strategic decisions, customer escalations

**Security Incidents**
- Contact: Security on-call (via incident management system)
- Response time: Immediate
- Use for: Security vulnerabilities, data breaches, compliance issues

For detailed escalation request format and weekly status template, see [docs/templates/risk-escalation-template.md](templates/risk-escalation-template.md).
