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

## Release Managers

### Role Summary
Release Managers coordinate the release process from planning through deployment and validation. They confirm pre-release requirements are met, schedule deployment windows, communicate with stakeholders, and ensure smooth releases with minimal risk.

### Responsibilities
- Plan and schedule release windows and deployment cadences
- Confirm all pre-release requirements are satisfied (tests, docs, approvals)
- Coordinate release communications with stakeholders and support teams
- Facilitate go/no-go decisions for releases
- Oversee deployment execution and post-release validation
- Maintain release documentation, notes, and retrospectives
- Manage rollback procedures when needed

### Goals
- Deliver reliable, predictable releases with minimal disruption
- Reduce deployment risk through thorough validation
- Maintain clear communication throughout the release cycle
- Continuously improve release processes and automation

### Interactions with Other Roles
- **Developers**: Validate code completion, test results, and merge status
- **Product Managers**: Align on feature readiness and release messaging
- **Project Managers**: Coordinate timelines, dependencies, and stakeholder updates
- **QA/Test Engineers**: Confirm acceptance criteria and test coverage
- **DevOps Engineers**: Collaborate on deployment automation and monitoring
- **Support Teams**: Provide release notes and prepare for customer inquiries
- **Technical Writers**: Ensure documentation is current and accurate

### Typical Communication
- Release planning meetings with cross-functional teams
- Go/no-go checkpoint meetings before deployments
- Release announcements and status updates to stakeholders
- Post-release summaries and retrospectives
- Incident coordination during deployment issues

---

## DevOps Engineers

### Role Summary
DevOps Engineers own CI/CD pipelines, deployment automation, infrastructure, and system reliability. They support Developers and Release Managers with tooling, monitoring, and incident response to ensure smooth, efficient delivery.

### Responsibilities
- Design, build, and maintain CI/CD pipelines
- Manage deployment automation and infrastructure as code
- Monitor system health, performance, and availability
- Implement security scanning and compliance checks
- Support incident response and troubleshooting
- Optimize build times and deployment efficiency
- Maintain development, staging, and production environments

### Goals
- Enable fast, reliable, automated deployments
- Maximize system uptime and reliability
- Reduce time to detect and resolve incidents
- Continuously improve tooling and automation

### Interactions with Other Roles
- **Developers**: Provide build tools, deployment support, and troubleshooting
- **Release Managers**: Execute deployments and provide infrastructure insights
- **Project Managers**: Report on infrastructure constraints and deployment risks
- **Security Teams**: Implement security controls and vulnerability scanning
- **QA/Test Engineers**: Support test environment setup and automation

### Typical Communication
- Daily syncs on build and deployment status
- Incident response coordination and post-mortems
- Infrastructure planning and capacity reviews
- Technical documentation for pipelines and tools
- On-call rotations and escalations

---

## UX Designers

### Role Summary
UX Designers are responsible for user experience, interface design, and usability. They collaborate with Product Managers and Developers throughout the product lifecycle to ensure solutions are intuitive, accessible, and aligned with user needs.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define user flows, information architecture, and interaction patterns
- Ensure accessibility standards are met
- Collaborate on design systems and component libraries
- Validate designs with users and stakeholders
- Provide design specifications and assets to Developers

### Goals
- Deliver intuitive, user-centered experiences
- Ensure consistency across products and platforms
- Improve user satisfaction and task completion rates
- Balance user needs with technical and business constraints

### Interactions with Other Roles
- **Product Managers**: Translate product vision into design concepts and user flows
- **Developers**: Collaborate on implementation feasibility and design handoff
- **QA/Test Engineers**: Define usability test scenarios and acceptance criteria
- **Technical Writers**: Align on user documentation and help content
- **Stakeholders**: Present designs and incorporate feedback

### Typical Communication
- Design review sessions with Product and Development teams
- User research findings and usability test results
- Design specifications and implementation guidance
- Feedback sessions and iteration discussions
- Design system updates and component documentation

---

## Technical Writers

### Role Summary
Technical Writers ensure all project and process documentation, user flows, release notes, and specifications are clear, current, and accessible. They serve both internal teams and external audiences, making complex information understandable.

### Responsibilities
- Create and maintain user documentation, guides, and tutorials
- Write release notes and change logs
- Document APIs, processes, and technical specifications
- Ensure documentation accuracy and completeness
- Organize and structure documentation for discoverability
- Collaborate with teams to gather information and validate content
- Establish documentation standards and templates

### Goals
- Make information easily accessible and understandable
- Reduce support burden through quality documentation
- Ensure documentation stays current with product changes
- Maintain consistent voice, style, and structure

### Interactions with Other Roles
- **Developers**: Gather technical details and validate implementation docs
- **Product Managers**: Document feature specifications and user stories
- **UX Designers**: Align on user flows and interface documentation
- **Release Managers**: Create release notes and deployment guides
- **Support Teams**: Provide customer-facing documentation and FAQs
- **Project Managers**: Document processes, decisions, and retrospectives

### Typical Communication
- Documentation review sessions with subject matter experts
- Content planning aligned with release schedules
- Feedback collection from users and support teams
- Style guide and template updates
- Knowledge base organization and maintenance

---

## Team Onboarding Checklist

This checklist helps new team members understand their role and integrate with the OctoAcme delivery process.

### For All New Team Members
- [ ] Review relevant role definition and responsibilities in this document
- [ ] Identify your key collaborators and schedule introductory meetings
- [ ] Understand project communication channels (Slack, email lists, meeting cadences)
- [ ] Access project boards, repos, and documentation repositories
- [ ] Review current project status and upcoming milestones
- [ ] Clarify escalation paths and decision-making authority

### Role-Specific Onboarding

#### Release Manager
- [ ] Review release schedule and upcoming deployments
- [ ] Access deployment tools and environments
- [ ] Review release playbooks and rollback procedures
- [ ] Join release planning and go/no-go meetings
- [ ] Meet with DevOps Engineers and establish deployment protocols

#### DevOps Engineer
- [ ] Get access to infrastructure, CI/CD, and monitoring tools
- [ ] Review architecture diagrams and deployment pipelines
- [ ] Join on-call rotation and review incident response procedures
- [ ] Review infrastructure as code repositories
- [ ] Meet with Developers to understand build and deployment needs

#### UX Designer
- [ ] Access design tools, libraries, and component systems
- [ ] Review existing user research and design artifacts
- [ ] Understand user personas and key user journeys
- [ ] Join design review sessions and sprint planning
- [ ] Meet with Product Managers to align on product vision

#### Technical Writer
- [ ] Access documentation repositories and publishing tools
- [ ] Review style guides and documentation standards
- [ ] Identify documentation gaps and improvement opportunities
- [ ] Join sprint planning to understand upcoming features
- [ ] Meet with Support teams to understand common user questions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

