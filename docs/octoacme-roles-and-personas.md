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
QA/Testing Leads define and execute quality assurance strategy, ensuring deliverables meet acceptance criteria and quality standards before release. They work closely with Developers and Product Managers to validate that features meet requirements and maintain quality standards throughout the delivery lifecycle.

### Responsibilities
- Create and maintain test plans and test cases
- Define QA and acceptance criteria alongside Product Managers
- Execute manual and automated testing across environments
- Identify and triage bugs; work with Developers on fixes
- Validate acceptance criteria before marking work "Done"
- Contribute to Definition of Done (DoD) and testing standards
- Provide quality dashboards and metrics to the team

### Goals
- Ensure high quality and reliability of releases
- Reduce production defects and incident rate
- Enable fast, confident deployments
- Build shared quality ownership across the team

### Interaction with Existing Roles
- **With Developers**: Collaborate on test coverage, bug prioritization, and acceptance criteria validation
- **With Product Managers**: Define quality expectations and acceptance criteria; validate features meet requirements
- **With Project Managers**: Report on quality status and risks; feed metrics into release readiness assessment

### Typical Communication
- Sprint planning and backlog refinement meetings
- Bug reports and test result summaries
- Quality dashboards and metrics
- Release readiness assessments

---

## Technical Lead/Architect

### Role Summary
Technical Leads provide architectural guidance, design reviews, and technical risk mitigation to ensure scalable, maintainable solutions. They mentor Developers, guide technical decisions, and collaborate with DevOps to ensure solutions are operationally sound.

### Responsibilities
- Review technical designs and provide architecture guidance
- Identify technical risks and propose mitigations
- Mentor Developers on technical standards and best practices
- Participate in code reviews for critical components
- Advise on technology choices and integration points
- Collaborate with DevOps on deployment and scalability concerns
- Contribute to technical risk register

### Goals
- Deliver technically sound, scalable solutions
- Reduce technical debt and rework
- Build team technical capability
- Ensure solutions align with long-term architecture vision

### Interaction with Existing Roles
- **With Developers**: Provide mentoring, design feedback, and technical standards
- **With Project Managers**: Identify and escalate technical risks and dependencies
- **With DevOps/Infrastructure Engineers**: Collaborate on architectural decisions affecting deployment and scalability

### Typical Communication
- Technical design reviews and architecture meetings
- Code review comments and mentoring
- Technical risk register contributions
- Architecture decision records (ADRs)

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove team impediments, and coach teams on agile practices and continuous improvement. They serve the entire team and work across all roles to optimize delivery flow and team health.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Remove blockers and escalate impediments
- Maintain sprint board and backlog health
- Coach team on agile principles and sustainable pace
- Protect team focus and manage meeting load
- Track and follow up on retrospective action items
- Foster psychological safety and continuous improvement culture

### Goals
- Optimize team velocity and flow
- Foster psychological safety and continuous improvement
- Remove non-delivery friction
- Build agile team maturity over time

### Interaction with Existing Roles
- **Cross-functional**: Works with all roles to remove impediments and facilitate ceremonies
- **With Project Managers**: Collaborate on timeline and capacity planning
- **With Developers**: Protect from context-switching; facilitate technical standups

### Typical Communication
- Agile ceremonies (standups, planning, retrospectives)
- One-on-ones with team members
- Blockers and escalation reports
- Impediment tracking and resolution

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders provide business context, align on priorities, and grant approvals for project direction and releases. They ensure the project remains connected to business objectives and secure necessary organizational support.

### Responsibilities
- Define business goals and success metrics
- Prioritize competing demands and trade-offs
- Provide approvals and gate decisions
- Communicate project status to senior leadership
- Ensure alignment across dependent teams
- Remove organizational blockers
- Validate business value realization post-release

### Goals
- Maximize business impact and ROI
- Align project delivery with strategy
- Maintain stakeholder confidence and engagement
- Enable informed decision-making across the organization

### Interaction with Existing Roles
- **With Product Managers**: Align on priorities and success metrics
- **With Project Managers**: Provide approvals, escalation resolution, and status communication
- **With Team**: Receive regular updates; provide business context and decisions

### Typical Communication
- Kickoff and planning reviews
- Monthly stakeholder updates
- Decision gates and approval requests
- Executive briefings and risk escalations

---

## UX/Design Lead

### Role Summary
UX/Design Leads define user experience strategy, create design artifacts, and ensure usability and consistency across products. They advocate for the user throughout the delivery process and collaborate with Developers to ensure designs are implementable and scalable.

### Responsibilities
- Conduct user research and define user stories/jobs-to-be-done
- Create wireframes, mockups, and design specifications
- Establish and maintain design systems and standards
- Participate in design reviews and provide feedback
- Validate usability through testing and iteration
- Collaborate with Developers on implementation fidelity
- Contribute to Definition of Done regarding user experience quality

### Goals
- Deliver intuitive, delightful user experiences
- Maintain design consistency and brand alignment
- Reduce user friction and support burden
- Build scalable design systems for efficient delivery

### Interaction with Existing Roles
- **With Product Managers**: Inform requirements through user research; validate solutions with users
- **With Developers**: Collaborate on implementation; provide design specifications and feedback
- **With QA/Testing Lead**: Define usability acceptance criteria; participate in user acceptance testing

### Typical Communication
- Design reviews and whiteboarding sessions
- Design specs and component documentation
- Usability testing results and feedback
- Design system updates and guidance

---

## DevOps/Infrastructure Engineer

### Role Summary
DevOps Engineers design and maintain deployment pipelines, infrastructure, and operational readiness for reliable, scalable production delivery. They enable the team to ship code safely and provide operational insights to inform architectural decisions.

### Responsibilities
- Design and maintain CI/CD pipelines
- Provision and manage environments (dev, staging, production)
- Implement monitoring, logging, and alerting
- Support incident response and rollback procedures
- Collaborate on deployment planning and release readiness
- Ensure security, compliance, and disaster recovery
- Provide operational feedback to inform design decisions

### Goals
- Enable fast, reliable, repeatable deployments
- Maintain high availability and performance
- Reduce manual toil and deployment risk
- Reduce mean time to recovery (MTTR) for incidents

### Interaction with Existing Roles
- **With Technical Lead/Architect**: Collaborate on scalability and deployment architecture
- **With Project Managers**: Support release planning; provide infrastructure capacity constraints
- **With Developers**: Support deployment; provide operational runbooks and monitoring guidance
- **With QA/Testing Lead**: Maintain test environments; support smoke testing in production

### Typical Communication
- Deployment planning and release checklists
- Infrastructure architecture reviews
- Incident post-mortems and runbook updates
- Operational metrics and capacity planning

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When planning cross-functional work, reference the "Interaction with Existing Roles" section to clarify communication and dependency patterns.
