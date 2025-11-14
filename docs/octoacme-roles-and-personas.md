# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Release Manager

### Role Summary
Release Managers orchestrate the end-to-end release process, ensuring that deployments are safe, coordinated, and well-communicated. They act as the single point of coordination for all release activities.

### Responsibilities
- Plan and schedule release windows
- Coordinate with Developers and QA during staging and production rollouts
- Ensure release checklists are completed
- Manage rollback procedures if issues arise
- Communicate release status to stakeholders
- Maintain release documentation and post-mortem reports

### Goals
- Execute zero-downtime deployments
- Minimize production incidents
- Ensure smooth coordination across teams during releases

### Typical Communication
- Release status updates to PM and stakeholders
- Go/no-go decisions with Quality Lead and Dev Lead
- Post-release summaries and metrics

### Interactions
Release Manager coordinates with Devs and QA during bake/stage phases, notifies Customer Success Lead for key customer-impacting releases, and escalates to PM if release risks emerge. Works closely with Quality Lead on release readiness sign-off.

---

## Customer Success Lead

### Role Summary
Customer Success Leads ensure that customers successfully adopt and derive value from the product. They act as the voice of the customer and coordinate responses to customer issues and feedback.

### Responsibilities
- Manage customer onboarding and training
- Monitor customer health metrics and usage patterns
- Coordinate responses to customer escalations
- Gather and prioritize customer feedback for Product Managers
- Communicate product updates and changes to customers
- Track customer satisfaction and retention metrics

### Goals
- Maximize customer satisfaction and retention
- Ensure customers achieve their desired outcomes
- Reduce time to value for new customers

### Typical Communication
- Customer health reviews and account updates
- Feature requests and feedback reports to Product Managers
- Release impact assessments and customer notifications
- Escalation coordination with Support and Engineering

### Interactions
Customer Success Lead receives release notifications from Release Manager about customer-impacting changes, escalates critical customer issues to PM and Stakeholders, and provides customer feedback to Product Managers (PdM) for roadmap planning. Works with QA on customer-reported issues.

---

## UX Designer

### Role Summary
UX Designers create intuitive, user-centered experiences by researching user needs, designing interfaces, and validating solutions through testing and iteration.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define user flows and interaction patterns
- Maintain design system and UI consistency
- Collaborate with Developers on implementation
- Validate designs through user feedback and analytics

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support requests
- Ensure design consistency across the product

### Typical Communication
- Design reviews and critique sessions
- User research findings and recommendations
- Design specifications and handoff documentation
- Usability test results and improvement proposals

### Interactions
UX Designer collaborates with Product Managers (PdM) on feature requirements and user needs, works closely with Developers on design implementation and feasibility, and partners with QA on acceptance criteria for user experience. Shares research insights with Stakeholders.

---

## Solutions Architect

### Role Summary
Solutions Architects design technical solutions that meet business requirements while ensuring scalability, security, and maintainability. They bridge business needs and technical implementation.

### Responsibilities
- Design system architecture and technical solutions
- Evaluate technology choices and trade-offs
- Define integration patterns and APIs
- Ensure non-functional requirements (performance, security, scalability)
- Review technical designs and provide guidance
- Document architectural decisions and patterns

### Goals
- Deliver scalable, maintainable solutions
- Minimize technical debt and rework
- Ensure alignment between business goals and technical implementation

### Typical Communication
- Architecture review boards and design reviews
- Technical specifications and architecture decision records
- Risk assessments and technical trade-off discussions
- Technical roadmap alignment with Product Managers

### Interactions
Solutions Architect works with Product Managers (PdM) and Stakeholders to understand business requirements, collaborates with Developers on technical design and implementation approaches, and coordinates with PM on technical risks and dependencies. Reviews security and scalability concerns with Quality Lead.

---

## Quality Lead

### Role Summary
Quality Leads define and maintain quality standards, oversee testing strategies, and ensure that releases meet quality and reliability requirements before reaching customers.

### Responsibilities
- Define quality standards and testing strategies
- Review test coverage and effectiveness
- Coordinate QA activities across the team
- Provide release readiness assessments
- Identify quality risks and improvement opportunities
- Ensure compliance with quality processes and regulations

### Goals
- Minimize defects reaching production
- Maintain high test coverage and reliability
- Enable fast, confident releases

### Typical Communication
- Quality metrics and test reports
- Release readiness sign-offs
- Quality improvement recommendations
- Risk assessments to PM and Release Manager

### Interactions
Quality Lead collaborates with Developers on testing approaches and coverage, partners with Release Manager on release readiness and go/no-go decisions, escalates quality risks to PM and Stakeholders, and works with QA team members on test execution and automation. Coordinates with Product Managers (PdM) on acceptance criteria clarity.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

