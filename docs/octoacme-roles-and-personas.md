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
- **Product Managers**: Collaborate on feature requirements and acceptance criteria
- **Project Managers**: Provide effort estimates and report on progress and technical risks
- **UX Designers**: Partner on design feasibility and implementation details
- **QA Automation Engineers**: Work together on test coverage and quality standards
- **Business Analysts**: Clarify requirements and validate technical solutions

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
- **Developers**: Define requirements and validate delivered features against success criteria
- **Project Managers**: Align on priorities, timelines, and resource allocation
- **UX Designers**: Collaborate on user research insights and feature design
- **Business Analysts**: Work together on requirements gathering and backlog refinement
- **Scrum Masters**: Partner on backlog prioritization and sprint planning

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
- **Product Managers**: Weekly syncs on priorities, scope, and stakeholder needs
- **Developers**: Track progress, manage dependencies, and facilitate planning
- **Scrum Masters**: Coordinate on team health, velocity, and impediment removal
- **QA Automation Engineers**: Monitor quality metrics and testing progress
- **Business Analysts**: Review requirements documentation and scope changes

---

## UX Designer

### Role Summary
UX Designers ensure user experience best practices are applied across the project lifecycle. They advocate for end-users and translate user research into intuitive designs.

### Responsibilities
- Conduct user research and usability testing
- Develop wireframes, mockups, and prototypes
- Collaborate with Product Managers and Developers to refine requirements
- Create design systems and maintain UI consistency
- Validate designs through user feedback and metrics

### Goals
- Create intuitive, accessible user experiences
- Reduce user friction and improve satisfaction
- Ensure design consistency across features

### Typical Communication
- Design reviews and feedback sessions
- Collaboration on user stories and acceptance criteria
- Prototype walkthroughs with stakeholders

### Interactions with Other Roles
- **Product Managers**: Works closely to understand feature requirements and user needs; provides design solutions that align with product vision
- **Developers**: Partners during implementation to ensure designs are feasible; provides design specs and assets
- **Business Analysts**: Collaborates on user flows and process improvements
- **QA/Testing**: Supports UAT planning and validates user experience in testing

---

## Scrum Master

### Role Summary
Scrum Masters facilitate Agile ceremonies and remove team impediments. They coach the team on Agile best practices and ensure smooth execution of sprints.

### Responsibilities
- Lead standups, sprint planning, reviews, and retrospectives
- Track sprint progress and team health metrics
- Remove blockers and facilitate conflict resolution
- Coach team on Agile principles and continuous improvement
- Protect the team from external interruptions

### Goals
- Maximize team velocity and efficiency
- Foster self-organization and accountability
- Maintain sustainable pace and team morale

### Typical Communication
- Daily facilitation of standup meetings
- Sprint metrics and burndown reports
- Retrospective summaries and action items

### Interactions with Other Roles
- **Developers**: Supports by removing impediments; facilitates technical discussions during ceremonies
- **Project Managers**: Coordinates on timelines and dependencies; reports on team health and sprint progress
- **Product Managers**: Ensures product backlog is ready for planning; facilitates prioritization discussions
- **QA Automation Engineers**: Helps coordinate testing efforts within sprint cycles

---

## QA Automation Engineer

### Role Summary
QA Automation Engineers design and maintain automated test suites to ensure product quality and reliability at scale.

### Responsibilities
- Develop and maintain test automation frameworks and scripts
- Integrate automated tests into CI/CD pipelines
- Collaborate with Developers on test coverage and quality metrics
- Identify and track defects through resolution
- Establish testing best practices and standards

### Goals
- Maximize test coverage and automation rate
- Reduce manual testing effort and time-to-feedback
- Ensure high product quality and reliability

### Typical Communication
- Test results and quality metrics reporting
- Bug reports and regression analysis
- Collaboration on acceptance criteria and test scenarios

### Interactions with Other Roles
- **Developers**: Partners on test strategy; reviews code for testability; collaborates on test coverage
- **Project Managers**: Reports on quality metrics and testing progress; flags quality risks
- **Product Managers**: Validates acceptance criteria are testable; provides feedback on feature quality
- **Scrum Master**: Coordinates testing activities within sprint workflow

---

## Business Analyst

### Role Summary
Business Analysts translate business requirements into actionable project deliverables. They bridge the gap between stakeholders and technical teams.

### Responsibilities
- Gather and document requirements from stakeholders
- Document process flows, data models, and acceptance criteria
- Support Product Managers in backlog refinement
- Analyze business processes and identify improvement opportunities
- Facilitate requirements workshops and validation sessions

### Goals
- Ensure clarity and completeness of requirements
- Minimize rework due to requirement ambiguity
- Enable data-driven decision making

### Typical Communication
- Requirements documents and user stories
- Process flow diagrams and data models
- Stakeholder meeting notes and decision records

### Interactions with Other Roles
- **Product Managers**: Supports requirements definition and backlog refinement; provides business analysis
- **Developers**: Clarifies requirements and acceptance criteria; validates technical feasibility
- **UX Designer**: Collaborates on user flows and process design
- **Project Managers**: Provides input on scope and dependencies; documents business requirements

---

## Role Onboarding Checklist

When a new team member joins in any of these roles, use this checklist to ensure smooth onboarding:

### Week 1: Orientation
- [ ] Access to all required systems and tools (GitHub, project boards, communication channels)
- [ ] Introduction to team members and their roles
- [ ] Review of project management overview and key artifacts
- [ ] Assigned an onboarding buddy/mentor
- [ ] Read all relevant process documentation in `docs/`

### Week 2: Role-Specific Setup
- [ ] Review role-specific responsibilities and goals
- [ ] Understand how your role interacts with other team members
- [ ] Access to role-specific tools (design tools for UX, test environments for QA, etc.)
- [ ] Shadow relevant meetings and ceremonies
- [ ] Review recent retrospectives and action items

### Week 3-4: Active Contribution
- [ ] Take on first assignment with mentor support
- [ ] Participate actively in team ceremonies
- [ ] Begin contributing to team deliverables
- [ ] Provide feedback on onboarding experience
- [ ] Schedule 30-day check-in with manager

### Ongoing
- [ ] Regularly review and update process documentation
- [ ] Participate in retrospectives and continuous improvement
- [ ] Share knowledge with team members
- [ ] Identify and escalate process gaps or inefficiencies

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

_Last updated: 2025-10-27 | Related to: Issue #4_

