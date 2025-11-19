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

## UX/UI Designer

### Role Summary
UX/UI Designers translate user and business needs into impactful interfaces, ensuring products are visually consistent, accessible, and easy to use.

### Responsibilities
- Collaborate with Product Managers on user research, prototyping, and defining UI requirements
- Work with Developers to implement designs and address usability concerns
- Conduct design reviews and usability testing
- Create wireframes, mockups, and design specifications
- Maintain design systems and style guides
- Advocate for accessibility and inclusive design practices

### Goals
- Create intuitive, user-friendly interfaces
- Ensure visual consistency across the product
- Reduce user friction and improve satisfaction scores
- Balance user needs with technical constraints

### Typical Communication
- Design review meetings with stakeholders
- Annotated mockups and interactive prototypes
- User testing reports and research findings
- Design handoff documentation for developers

### Collaboration with Other Roles
- **Product Managers**: Align on user needs, requirements, and success metrics
- **Developers**: Provide design specs, review implementation, address technical constraints
- **QA/Testing**: Collaborate on usability testing and accessibility validation
- **Technical Writers**: Share UI terminology and user flow documentation

---

## Technical Writer

### Role Summary
Technical Writers create and maintain product documentation, including internal guides, user-facing instructions, and API references.

### Responsibilities
- Gather information from Developers and Product Managers
- Author and update documentation, FAQs, and release notes
- Ensure clarity, accuracy, and accessibility of information
- Maintain documentation style guides and templates
- Review technical content for consistency and quality
- Coordinate documentation releases with product launches

### Goals
- Make complex technical information accessible
- Reduce support tickets through clear documentation
- Keep documentation current with product changes
- Improve onboarding and user self-service

### Typical Communication
- Project documentation and user guides
- Onboarding manuals and tutorials
- Release notes and change logs
- Internal knowledge base articles

### Collaboration with Other Roles
- **Developers**: Gather technical details, review accuracy, coordinate releases
- **Product Managers**: Align on feature priorities and user-facing messaging
- **Customer Success/Support**: Incorporate feedback, address common questions
- **UX/UI Designers**: Ensure documentation matches UI and user flows

---

## DevOps/Site Reliability Engineer (SRE)

### Role Summary
DevOps/SRE engineers ensure reliable, scalable infrastructure and streamlined deployment processes. They bridge development and operations to maintain system health and enable rapid delivery.

### Responsibilities
- Manage CI/CD pipelines and deployment automation
- Monitor system performance, availability, and reliability
- Implement infrastructure as code and configuration management
- Respond to incidents and conduct post-mortems
- Define and track service level objectives (SLOs) and error budgets
- Optimize system performance and cost efficiency

### Goals
- Maintain high system availability and reliability
- Reduce deployment friction and cycle time
- Automate repetitive operational tasks
- Improve observability and incident response

### Typical Communication
- Incident reports and post-mortem documents
- System health dashboards and SLO reports
- Deployment runbooks and operational guides
- Infrastructure change proposals

### Collaboration with Other Roles
- **Developers**: Enable smooth deployments, share operational insights, improve reliability
- **Project Managers**: Coordinate release schedules, communicate infrastructure dependencies
- **Product Managers**: Balance feature velocity with reliability needs
- **Business Analysts**: Provide system usage data and performance metrics

---

## Business Analyst

### Role Summary
Business Analysts bridge business requirements and technical implementation, ensuring solutions deliver measurable business value and meet stakeholder needs.

### Responsibilities
- Gather and analyze business requirements from stakeholders
- Document workflows, processes, and system requirements
- Perform data analysis to support decision-making
- Create business cases and ROI projections
- Facilitate requirements workshops and stakeholder meetings
- Validate that solutions meet business objectives

### Goals
- Ensure solutions address actual business problems
- Provide data-driven insights for prioritization
- Reduce requirements ambiguity and rework
- Improve alignment between business and technical teams

### Typical Communication
- Requirements documents and user stories
- Business process diagrams and workflows
- Data analysis reports and dashboards
- Stakeholder presentation decks

### Collaboration with Other Roles
- **Product Managers**: Validate business value, prioritize features, define success metrics
- **Developers**: Clarify requirements, provide context, review implementations
- **Project Managers**: Support planning, track dependencies, assess risks
- **Customer Success/Support**: Gather user feedback and usage patterns

---

## Customer Success/Support Lead

### Role Summary
Customer Success/Support Leads ensure customers achieve their desired outcomes with the product and serve as the voice of the customer within the organization.

### Responsibilities
- Manage customer onboarding and adoption
- Provide product support and troubleshooting
- Gather customer feedback and feature requests
- Track customer health metrics and engagement
- Coordinate escalations and critical issues
- Advocate for customer needs in product decisions

### Goals
- Maximize customer satisfaction and retention
- Reduce time to value for new customers
- Identify and address pain points proactively
- Build strong customer relationships and advocacy

### Typical Communication
- Customer support tickets and resolutions
- Onboarding guides and training materials
- Feedback reports and feature request summaries
- Customer health scorecards and engagement metrics

### Collaboration with Other Roles
- **Product Managers**: Share customer insights, prioritize feature requests, validate solutions
- **Technical Writers**: Improve documentation based on support patterns
- **Developers**: Report bugs, clarify feature behavior, coordinate fixes
- **Business Analysts**: Provide usage data and customer trends

---

## Cross-Role Collaboration and Handoffs

### Design to Development
**Key Handoff Points:**
- Design specifications and mockups reviewed and approved
- Interactive prototypes or design system components ready
- Accessibility requirements documented
- Edge cases and responsive behavior defined

**Checklist:**
- [ ] Design review completed with stakeholders
- [ ] All design assets exported and accessible
- [ ] Developer questions addressed
- [ ] Acceptance criteria includes design compliance

### Development to QA/Testing
**Key Handoff Points:**
- Feature complete and ready for testing
- Test environment prepared and accessible
- Known limitations or issues documented
- Acceptance criteria clearly defined

**Checklist:**
- [ ] Code merged to test branch
- [ ] Test data prepared if needed
- [ ] Demo or walkthrough provided
- [ ] Edge cases and error scenarios documented

### Product to Technical Writing
**Key Handoff Points:**
- Feature functionality finalized
- User-facing changes identified
- Release timeline confirmed
- Target audience and use cases clarified

**Checklist:**
- [ ] Feature overview and user flows shared
- [ ] UI terminology and screenshots provided
- [ ] Known limitations or prerequisites documented
- [ ] Review timeline agreed upon

### Development to DevOps/SRE
**Key Handoff Points:**
- Deployment requirements specified
- Infrastructure needs identified
- Monitoring and alerting defined
- Rollback plan documented

**Checklist:**
- [ ] Deployment guide reviewed
- [ ] Infrastructure changes tested
- [ ] Monitoring dashboards configured
- [ ] Incident runbook updated

### Customer Feedback to Product/Development
**Key Handoff Points:**
- Feature requests prioritized and clarified
- Bug reports reproduced and documented
- Customer impact assessed
- Resolution timeline communicated

**Checklist:**
- [ ] Feedback categorized and summarized
- [ ] Priority and impact assigned
- [ ] Technical feasibility reviewed
- [ ] Customer expectation set

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The cross-role collaboration section provides practical scenarios for improving handoffs and communication.

