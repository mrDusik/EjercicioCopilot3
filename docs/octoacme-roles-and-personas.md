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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality assurance strategy, test planning, and validation of deliverables against acceptance criteria. They collaborate with developers and product teams to ensure features meet quality standards before release.

### Responsibilities
- Define and maintain QA strategy and test approach for the project
- Create and maintain test plans, test cases, and automation frameworks
- Validate that deliverables meet acceptance criteria and Definition of Done
- Execute manual and automated testing (unit, integration, end-to-end)
- Identify and track quality issues and defects
- Conduct smoke tests before release and verify post-deployment
- Advise on testability during design and planning phases

### Goals
- Ensure high-quality releases with minimal production defects
- Provide early feedback on quality risks
- Build confidence in system reliability through comprehensive testing

### Typical Communication
- Sprint planning and backlog refinement (for testability input)
- Daily standups (quality metrics and testing progress)
- Pre-release smoke test coordination
- Quality dashboards and defect reports

### Interactions with Existing Roles
- **Developers**: Reviews code for testability, provides test guidance, validates implementation against test cases
- **Product Managers**: Collaborates on acceptance criteria definition and prioritization of quality-impacting features
- **Project Managers**: Reports quality metrics and risks, coordinates testing timeline with delivery schedule

---

## Technical Lead/Architect

### Role Summary
Technical Leads provide architectural guidance, design reviews, and technical risk mitigation. They partner with product and project leadership to ensure solutions are scalable, maintainable, and aligned with technical strategy.

### Responsibilities
- Review and approve technical designs and architecture decisions
- Identify technical risks and propose mitigations
- Mentor developers and support technical problem-solving
- Ensure adherence to coding standards and architectural principles
- Evaluate technology choices and trade-offs
- Coordinate integration points and dependencies with other systems

### Goals
- Deliver scalable, maintainable solutions
- Reduce technical debt and long-term maintenance risk
- Enable team velocity through sound architecture

### Typical Communication
- Design review meetings and technical discussions
- Code reviews and architectural guidance
- Risk register contributions (technical risks)
- Sprint planning (for technical estimation and feasibility)

### Interactions with Existing Roles
- **Developers**: Provides technical guidance, reviews designs and code, mentors on best practices
- **Product Managers**: Advises on technical feasibility and constraints, proposes architectural trade-offs
- **Project Managers**: Contributes technical risks to risk register, communicates technical timeline impacts

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, approve scope, allocate resources, and ensure alignment with organizational strategy. They are the primary decision-makers and authority for project governance.

### Responsibilities
- Define business need and strategic alignment
- Approve project charter and success metrics
- Make go/no-go decisions at key gates
- Allocate budget and resources
- Escalate blockers and remove organizational barriers
- Provide feedback and approval on major milestones
- Communicate project status to their own leadership

### Goals
- Ensure project delivers measurable business value
- Minimize scope creep and rework
- Maintain alignment with organizational priorities

### Typical Communication
- Project initiation and kickoff meetings
- Milestone reviews and gate decisions
- Monthly stakeholder updates
- Escalation path for business-blocking issues

### Interactions with Existing Roles
- **Developers**: Reviews technical feasibility of scope, approves high-impact architectural decisions
- **Product Managers**: Aligns on strategic priorities, approves roadmap and success metrics
- **Project Managers**: Receives status updates, makes approval decisions at gates, escalates business-impacting risks

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove team impediments, and coach the team on agile practices. They serve the team by enabling focus and continuous improvement.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Identify and help resolve team blockers and impediments
- Coach the team on agile practices and continuous improvement
- Maintain sprint board and track team metrics (velocity, burndown)
- Protect the team from external distractions
- Support Definition of Done and sprint goals

### Goals
- Enable consistent team velocity and predictability
- Foster continuous improvement culture
- Remove friction from the development process

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective facilitation and action item tracking
- Impediment escalation to Project Manager
- Metrics reporting to Project Lead

### Interactions with Existing Roles
- **Developers**: Facilitates ceremonies, removes blockers, coaches on agile practices
- **Product Managers**: Coordinates sprint planning and backlog refinement, reports team velocity
- **Project Managers**: Escalates impediments, reports team capacity and metrics

---

## Security Lead

### Role Summary
Security Leads integrate security into all project phases, conduct threat assessments, manage security scanning and compliance, and lead incident response. They ensure the project meets security standards and regulatory requirements.

### Responsibilities
- Conduct threat assessments and security design reviews
- Define security requirements and acceptance criteria
- Configure and monitor security scanning in CI/CD
- Review and approve security-related changes
- Prepare and execute security incident playbooks
- Ensure compliance with security policies and regulations
- Advise on secure coding practices and architecture patterns

### Goals
- Build secure solutions that protect customer and organizational data
- Minimize security-related production incidents
- Maintain compliance and audit readiness

### Typical Communication
- Design and planning reviews (security input)
- Security incident response and post-mortems
- Release checklists and pre-deploy verification
- Security dashboards and vulnerability tracking

### Interactions with Existing Roles
- **Developers**: Reviews code for security issues, advises on secure coding practices, leads incident response
- **Product Managers**: Incorporates security requirements into acceptance criteria, prioritizes security features
- **Project Managers**: Contributes security risks to risk register, coordinates security reviews in release timeline

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
