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

### Interactions with Other Roles
- Collaborate with **QA/Testing Lead** on test planning and acceptance testing
- Work with **Technical Lead/Architect** on design reviews and technical decisions
- Receive requirements from **Product Managers** and status to **Project Managers**
- Follow security guidance from **Security Engineer** in code implementation
- Support **Support/Operations** with incident response and troubleshooting

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

### Interactions with Other Roles
- Align with **Stakeholders/Sponsors** on business requirements and priorities
- Work with **Project Managers** to translate vision into plans
- Collaborate with **Technical Lead/Architect** on feasibility and technical trade-offs
- Partner with **QA/Testing Lead** on acceptance criteria and quality standards
- Engage **Security Engineer** on security requirements and compliance needs

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

### Interactions with Other Roles
- Report progress and risks to **Stakeholders/Sponsors**
- Coordinate between **Developers**, **QA/Testing Lead**, and **Technical Lead/Architect**
- Work with **Security Engineer** on security review scheduling
- Collaborate with **Support/Operations** on release planning and deployment
- Align with **Product Managers** on scope and timeline

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, test planning, and validation of acceptance criteria across the project lifecycle. They ensure product quality and confidence before release.

### Responsibilities
- Define test approach (unit, integration, end-to-end, security scanning)
- Create and maintain test plans aligned with project milestones
- Conduct acceptance testing against documented criteria
- Identify and log quality issues with severity and reproducibility
- Validate fixes and sign-off on feature completion
- Participate in release readiness reviews
- Advise on testability and quality risks

### Goals
- Ensure product quality and reliability
- Catch defects early in the development cycle
- Enable confidence in releases and deployments
- Minimize post-release incidents

### Typical Communication
- Sprint planning and daily standups
- PR reviews and test result reports
- Release checklists and quality gates
- Issue logging and defect tracking

### Interactions with Other Roles
- Collaborate with **Developers** on test planning and acceptance criteria
- Review acceptance criteria with **Product Managers**
- Advise **Technical Lead/Architect** on testability of technical designs
- Coordinate with **Security Engineer** on security testing requirements
- Support **Project Managers** with quality metrics and release readiness
- Work with **Support/Operations** on smoke tests and post-deploy verification

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, approve scope and budget, and receive regular status updates. They ensure project alignment with organizational strategy and business objectives.

### Responsibilities
- Define business requirements and success metrics
- Approve project initiation and resource allocation
- Make decisions on scope trade-offs and priorities
- Receive and review milestone and release communications
- Escalate business-impacting blockers
- Provide business context and competitive landscape insights
- Validate that delivered solutions meet business goals

### Goals
- Deliver business value and ROI
- Minimize business risk and ensure organizational alignment
- Ensure consistent communication of project status
- Enable timely decision-making on trade-offs

### Typical Communication
- Project kickoff and initiation meetings
- Milestone reviews and progress gates
- Monthly stakeholder updates and executive briefings
- Escalation meetings for business-impacting issues

### Interactions with Other Roles
- Work with **Project Managers** for status updates and escalation
- Align with **Product Managers** on business objectives and success metrics
- Review deliverables from **Developers** through quality checkpoints
- Receive release communications from **Support/Operations**
- Approve scope and timeline with full team

---

## Security Engineer

### Role Summary
Security Engineers ensure security requirements are defined, implemented, and validated throughout the project lifecycle. They enable secure development practices and reduce security risk.

### Responsibilities
- Review security requirements and threat models
- Advise on secure coding practices and secure architecture patterns
- Configure and maintain security scanning in CI/CD pipeline
- Conduct or coordinate security testing and code reviews before release
- Respond to and triage security incidents
- Update security documentation and incident runbooks
- Provide security training and guidance to development teams

### Goals
- Minimize security vulnerabilities in delivered software
- Enable secure deployment and operations
- Support incident response and reduce security risk
- Maintain compliance with security standards and regulations

### Typical Communication
- Design reviews and architecture discussions
- Sprint planning and security requirement sessions
- Security scan reports and pre-release reviews
- Incident response coordination
- Security training and best practice guidance

### Interactions with Other Roles
- Advise **Developers** on secure coding and identify security risks in code
- Review security requirements with **Product Managers**
- Conduct security reviews with **Technical Lead/Architect**
- Include security testing in **QA/Testing Lead** test plans
- Brief **Project Managers** on security risks and mitigation timelines
- Coordinate deployment security checks with **Support/Operations**
- Report security posture to **Stakeholders/Sponsors**

---

## Technical Lead/Architect

### Role Summary
Technical Leads and Architects guide technical strategy, design decisions, and system architecture to support project goals. They ensure scalable, maintainable solutions aligned with organizational standards.

### Responsibilities
- Define technical approach and architecture for the project
- Review and advise on major design decisions
- Identify technical risks and propose mitigations
- Mentor developers on best practices and design patterns
- Participate in code and design reviews
- Ensure alignment with platform standards, dependencies, and organizational guidelines
- Lead technical feasibility assessments and trade-off analysis

### Goals
- Deliver scalable, maintainable solutions
- Minimize technical debt and architectural complexity
- Ensure architectural coherence across projects
- Enable high-performance and reliable systems

### Typical Communication
- Kickoff and planning meetings with technical team
- Design discussions and architecture reviews
- Code reviews and mentoring sessions
- Risk register updates and technical feasibility assessments
- Alignment discussions with **Security Engineer**

### Interactions with Other Roles
- Mentor and guide **Developers** on technical implementation
- Advise **Product Managers** on technical feasibility and trade-offs
- Collaborate with **QA/Testing Lead** on test strategy and performance requirements
- Partner with **Security Engineer** on secure architecture and threat modeling
- Update **Project Managers** on technical risks and mitigation plans
- Coordinate with **Support/Operations** on operational requirements and scalability

---

## Support/Operations

### Role Summary
Support and Operations teams prepare for and manage operational aspects of deployed features, including post-release verification, monitoring, and incident response. They ensure smooth releases and stable operations.

### Responsibilities
- Participate in release planning and deployment scheduling
- Execute deployment runbooks and post-deploy verifications
- Monitor dashboards and key signals post-release
- Respond to production incidents and escalate as needed
- Communicate issues to on-call teams
- Capture operational insights for retrospectives
- Manage rollback procedures if issues are detected
- Document operational runbooks and playbooks

### Goals
- Ensure smooth releases and stable production operations
- Enable rapid incident response and resolution
- Maintain continuous visibility into system health
- Support team learning from operational incidents

### Typical Communication
- Release kickoff and deployment day coordination
- Incident response and escalation
- Operational metrics and dashboard reviews
- Retrospective participation and action item capture

### Interactions with Other Roles
- Coordinate with **Project Managers** on release timing and dependencies
- Execute deployment guidance from **Developers** and **Technical Lead/Architect**
- Validate acceptance criteria with **QA/Testing Lead** through smoke tests
- Follow security procedures from **Security Engineer** during deployments
- Report operational status to **Stakeholders/Sponsors**
- Provide operational feedback to **Developers** for incident prevention
- Collaborate with **Product Managers** on feature rollout strategy

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction patterns to understand how roles collaborate throughout the project lifecycle.
