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

### Interactions with Other Personas
- **QA/Test Engineers**: Collaborate on acceptance criteria, respond to defect reports, and support test automation efforts
- **Technical Leads/Architects**: Follow technical designs and architecture guidance, participate in design reviews
- **Project Managers**: Provide estimates and status updates, help identify risks and blockers
- **Scrum Masters/Agile Coaches**: Participate in ceremonies and report impediments
- **Product Managers**: Clarify requirements and acceptance criteria

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

### Interactions with Other Personas
- **Developers**: Define requirements and acceptance criteria, provide feedback on solutions
- **QA/Test Engineers**: Define quality standards and acceptance criteria, review test plans
- **Project Managers**: Align on scope and priorities, communicate with stakeholders
- **Technical Leads/Architects**: Discuss technical feasibility and trade-offs
- **Stakeholders/Business Owners**: Validate alignment with business objectives

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

### Interactions with Other Personas
- **Scrum Masters/Agile Coaches**: Coordinate on process and team health
- **Stakeholders/Business Owners**: Escalate risks and trade-offs, provide status updates
- **Developers**: Track progress and identify blockers
- **Operations/DevOps Engineers**: Coordinate on deployment readiness and operational risks
- **Technical Leads/Architects**: Factor technical risks and dependencies into plans

---

## QA/Test Engineers

### Role Summary
QA/Test Engineers ensure product quality through comprehensive testing, automation, and defect identification. They collaborate with Developers and Product Managers to define acceptance criteria, validate requirements, and maintain quality standards throughout the delivery lifecycle.

### Responsibilities
- Design and execute manual and automated test cases
- Identify, document, and track defects
- Validate acceptance criteria before release
- Collaborate on test strategy and coverage planning
- Participate in requirements refinement and acceptance criteria definition
- Support performance and security testing efforts

### Goals
- Ensure product meets quality standards and acceptance criteria
- Reduce production defects and customer-facing issues
- Provide early feedback to catch issues before production

### Typical Communication
- Daily standups and sprint planning
- Test case reviews and defect reports
- Acceptance criteria discussions with Product Managers
- Quality metrics and dashboard reviews

### Interactions with Other Personas
- **Developers**: Report defects, collaborate on test automation, provide feedback on testability
- **Product Managers**: Refine acceptance criteria, validate requirements align with quality standards
- **Technical Leads/Architects**: Understand technical architecture and design for testability
- **Project Managers**: Report quality metrics and test coverage status
- **Operations/DevOps Engineers**: Collaborate on performance and security testing requirements

---

## Technical Leads/Architects

### Role Summary
Technical Leads/Architects define technical strategy, design system architecture, and guide engineering decisions. They ensure solutions are scalable, maintainable, and aligned with long-term technical vision.

### Responsibilities
- Define technical architecture and design patterns
- Guide technology and tool selection decisions
- Review and approve technical designs and proposals
- Mentor developers and drive technical excellence
- Identify and mitigate technical risks
- Ensure alignment with system performance and security requirements

### Goals
- Build scalable, maintainable solutions
- Reduce technical debt and improve system health
- Guide team toward technical excellence and best practices

### Typical Communication
- Technical design reviews and architecture discussions
- Technical risk assessments and mitigation plans
- Code review guidance and mentoring sessions
- Technology roadmap and strategic planning

### Interactions with Other Personas
- **Developers**: Provide architectural guidance, review designs, mentor on technical excellence
- **QA/Test Engineers**: Define testability requirements and non-functional testing strategies
- **Project Managers**: Identify technical risks and dependencies that impact the plan
- **Operations/DevOps Engineers**: Collaborate on performance, scalability, and operational requirements
- **Product Managers**: Advise on technical feasibility and trade-offs

---

## Scrum Masters/Agile Coaches

### Role Summary
Scrum Masters/Agile Coaches facilitate agile practices, remove blockers, and help teams continuously improve their delivery processes.

### Responsibilities
- Facilitate sprint ceremonies (standups, planning, reviews, retrospectives)
- Coach team on agile principles and practices
- Identify and help resolve team impediments
- Track team velocity and process metrics
- Support process improvement initiatives
- Advocate for team well-being and sustainable pace

### Goals
- Enable team to deliver value consistently and predictably
- Improve team collaboration and communication
- Continuously improve delivery processes and practices

### Typical Communication
- Sprint ceremonies and process check-ins
- Retrospective outcomes and improvement actions
- Blockers and impediment resolution
- Team health and velocity tracking

### Interactions with Other Personas
- **Developers**: Remove impediments, facilitate collaboration, coach on agile principles
- **Project Managers**: Coordinate on dependencies and escalations beyond team control
- **Product Managers**: Facilitate backlog refinement and prioritization discussions
- **All Personas**: Facilitate ceremonies and communications to keep team aligned

---

## Stakeholders/Business Owners

### Role Summary
Stakeholders/Business Owners represent business interests, define success criteria, and ensure projects align with organizational goals and customer needs.

### Responsibilities
- Define business objectives and success metrics
- Provide business context and strategic direction
- Make key trade-off decisions between scope, schedule, and resources
- Validate solutions meet business needs
- Communicate with executive leadership
- Address escalations and remove organizational blockers

### Goals
- Ensure projects deliver business value and ROI
- Align delivery with organizational strategy
- Maintain stakeholder confidence and trust

### Typical Communication
- Executive steering committee meetings
- Business requirement discussions
- High-level status updates and milestone reviews
- Decision-making forums for trade-offs and escalations

### Interactions with Other Personas
- **Project Managers**: Provide strategic direction, make trade-off decisions, receive status reports
- **Product Managers**: Validate product vision aligns with business strategy
- **Scrum Masters/Agile Coaches**: Understand business context and strategic priorities
- **All Personas**: Set business objectives and success criteria that guide delivery

---

## Operations/DevOps Engineers

### Role Summary
Operations/DevOps Engineers enable reliable, scalable deployment and operation of solutions. They bridge development and production, ensuring infrastructure readiness and operational excellence.

### Responsibilities
- Design and maintain deployment pipelines and infrastructure
- Support release planning and deployment activities
- Monitor production systems and respond to incidents
- Collaborate on performance, security, and reliability requirements
- Document runbooks and operational procedures
- Identify operational risks and propose mitigations

### Goals
- Enable fast, safe, reliable deployments
- Maintain high system availability and performance
- Reduce deployment risk and operational toil

### Typical Communication
- Release planning and deployment coordination
- Infrastructure readiness reviews
- Incident response and root cause analysis
- Operational metrics and performance reviews

### Interactions with Other Personas
- **Developers**: Provide deployment infrastructure, support incident response, share operational learnings
- **Technical Leads/Architects**: Collaborate on scalability and performance requirements
- **Project Managers**: Report on infrastructure readiness and operational risks
- **QA/Test Engineers**: Collaborate on performance and security testing
- **Product Managers**: Provide operational insights that influence feature design

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-persona interactions illustrate how different roles depend on and communicate with each other throughout the project lifecycle.
