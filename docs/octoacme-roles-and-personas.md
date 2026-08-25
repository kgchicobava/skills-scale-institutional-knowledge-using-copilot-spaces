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

## Quality Assurance Lead

### Role Summary
Quality Assurance Leads develop and execute testing strategies, manage defect resolution, and enforce quality gates throughout the project lifecycle. They ensure deliverables meet acceptance criteria and quality standards before release.

### Responsibilities
- Develop and execute testing strategies for project phases
- Manage defect identification, prioritization, and resolution tracking
- Define and enforce quality gates and acceptance standards before release
- Report quality metrics and risk assessments to the Project Manager
- Collaborate with Developers to reproduce, analyze, and resolve defects
- Plan and coordinate user acceptance testing activities

### Goals
- Ensure product quality and reliability
- Reduce defects in production through early detection
- Maintain transparency on quality status and risks
- Enable efficient defect resolution and release readiness

### Interactions with Existing Roles
- **Works with Developers**: Collaborates on defect reproduction, root cause analysis, and resolution verification
- **Coordinates with Project Manager**: Provides quality status updates, escalates quality risks, and aligns on quality milestones
- **Reports to Project Sponsor**: Communicates quality risk assessments and release readiness decisions
- **Supports Product Managers**: Validates acceptance criteria and participates in scope discussions related to quality implications

### Typical Communication
- Daily defect tracking and status updates
- Quality metrics and trend reports
- Defect prioritization and resolution discussions
- Release readiness assessments

---

## Infrastructure/DevOps Engineer

### Role Summary
Infrastructure/DevOps Engineers manage deployment environments, infrastructure requirements, and continuous integration/deployment pipelines. They enable reliable, efficient delivery of software to production.

### Responsibilities
- Manage and maintain development, staging, and production environments
- Coordinate infrastructure requirements and capacity planning
- Implement and maintain CI/CD pipelines and automation
- Support production deployments, rollbacks, and incident response
- Monitor system performance and manage infrastructure scaling
- Document infrastructure configurations and runbooks

### Goals
- Enable fast, reliable, and repeatable deployments
- Minimize deployment-related downtime and incidents
- Ensure infrastructure meets performance and availability requirements
- Reduce manual effort through automation

### Interactions with Existing Roles
- **Collaborates with Developers**: Reviews deployment requirements, supports infrastructure-as-code implementations, provides deployment guidance
- **Coordinates with Project Manager**: Provides infrastructure status updates, communicates deployment readiness, escalates infrastructure risks
- **Partners with Release Manager**: Participates in release planning, coordinates deployment windows, manages production rollouts
- **Works with Security Officer**: Implements security controls, manages access credentials, ensures compliance with security policies

### Typical Communication
- Deployment planning and coordination meetings
- Infrastructure status and performance reports
- Incident response and post-mortems
- Release coordination and deployment schedules

---

## Business Analyst

### Role Summary
Business Analysts bridge business and technical teams by capturing requirements, validating acceptance criteria, and ensuring solutions address business needs. They facilitate clear communication and shared understanding across stakeholders.

### Responsibilities
- Capture and document business requirements and user stories
- Validate acceptance criteria with stakeholders and engineering teams
- Facilitate requirements gathering sessions with business stakeholders
- Clarify ambiguities and resolve conflicts in requirements
- Support user acceptance testing and validation activities
- Document business processes and system workflows

### Goals
- Ensure solutions align with business objectives
- Reduce rework due to misunderstood requirements
- Enable clear communication between business and technical teams
- Facilitate efficient scope management and change control

### Interactions with Existing Roles
- **Partners with Product Managers**: Collaborates on requirement prioritization, scope definition, and stakeholder engagement
- **Engages with Developers**: Clarifies technical feasibility, discusses implementation approaches, provides requirement context
- **Coordinates with Project Managers**: Manages requirement changes, supports scope management, facilitates stakeholder alignment
- **Supports Quality Assurance**: Validates acceptance criteria, participates in test planning, supports UAT coordination

### Typical Communication
- Requirements documentation and user story specifications
- Stakeholder feedback and clarification sessions
- Change request discussions and impact analysis
- UAT planning and execution coordination

---

## Security Officer

### Role Summary
Security Officers review project processes, activities, and deliverables for security and compliance requirements. They identify security risks and ensure appropriate controls are implemented to protect organizational assets.

### Responsibilities
- Review project processes and deliverables for security and compliance implications
- Identify security risks and recommend mitigation strategies
- Approve security controls and risk mitigation approaches
- Conduct security reviews and assessments before release
- Ensure compliance with security policies and regulatory requirements
- Advise on secure development practices and data protection

### Goals
- Protect organizational and customer data
- Ensure compliance with security policies and regulations
- Reduce security-related risks and incidents
- Foster a security-aware culture within project teams

### Interactions with Existing Roles
- **Advises Project Managers**: Communicates security requirements, escalates security risks, reviews project plans for compliance implications
- **Reviews Developer Work**: Conducts code and architecture security reviews, provides secure coding guidance
- **Collaborates with Quality Assurance**: Coordinates security testing activities, validates security acceptance criteria
- **Works with Infrastructure/DevOps**: Reviews infrastructure configurations, ensures secure access controls, validates deployment security

### Typical Communication
- Security requirements and compliance assessments
- Risk assessments and mitigation strategies
- Security review findings and remediation tracking
- Compliance audit and certification communications

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When scenarios involve quality, infrastructure, analysis, or security decisions, reference the appropriate persona for role context.
