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

### Key Interactions
- **Product Managers**: Clarify requirements, discuss technical feasibility and trade-offs
- **Project Managers**: Report progress, identify blockers and dependencies
- **QA/Testing**: Collaborate on test cases, reproduce and fix bugs
- **UX Designer**: Review designs, discuss implementation approach
- **DevOps Engineer**: Integrate with CI/CD, troubleshoot deployment issues
- **Security Lead**: Address security vulnerabilities, implement security requirements
- **Other Developers**: Code reviews, pair programming, knowledge sharing

### Example Scenario
A developer is implementing a new feature for user notifications. They review the design with the UX Designer to understand the user flow, work with the Product Manager to clarify edge cases, implement the feature with test coverage, submit a PR for code review, address security feedback from the Security Lead about data encryption, and collaborate with DevOps to ensure the feature works in the staging environment before release.

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

### Key Interactions
- **Developers**: Define requirements, discuss technical constraints and feasibility
- **Project Managers**: Align on roadmap, coordinate sprint planning and priorities
- **UX Designer**: Collaborate on user research, validate design solutions against user needs
- **QA/Testing**: Define acceptance criteria and quality expectations
- **Stakeholders**: Communicate product vision, gather feedback, manage expectations
- **Security Lead**: Prioritize security work, balance security and feature delivery
- **Release Manager**: Coordinate release content and timing

### Example Scenario
A Product Manager identifies through user feedback that customers need bulk data export capabilities. They work with the UX Designer to understand the workflow, prioritize this feature on the roadmap with Stakeholders, collaborate with Developers to define technical approach and estimate effort, coordinate with the Project Manager to schedule the work, and define clear acceptance criteria with QA. After release, they measure adoption metrics to validate the feature's impact.

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

### Key Interactions
- **Product Managers**: Align on priorities, scope changes, and timeline
- **Developers**: Track progress, identify and remove blockers, coordinate dependencies
- **QA/Testing**: Ensure testing is planned and capacity is available
- **Release Manager**: Coordinate release schedules and deployment planning
- **UX Designer**: Track design deliverable timelines, coordinate design reviews
- **DevOps Engineer**: Plan infrastructure needs and deployment windows
- **Security Lead**: Schedule security reviews in project timeline
- **Stakeholders**: Provide status updates, escalate issues, seek decisions and approvals

### Example Scenario
A Project Manager coordinates a multi-team initiative to launch a new mobile app. They facilitate the kickoff meeting with all roles, create a detailed project plan with milestones, maintain a risk register tracking a potential API dependency, coordinate weekly syncs between Product, Design, and Engineering, escalate a resource constraint to Stakeholders, work with the Release Manager to plan the phased rollout, and ensure security reviews are completed before each release phase.

---

## QA / Testing

### Role Summary
QA professionals ensure product quality by validating features against acceptance criteria, identifying defects, and verifying that releases meet quality standards before deployment.

### Responsibilities
- Create and execute test plans and test cases
- Perform functional, integration, and regression testing
- Identify, document, and track defects
- Collaborate with developers to reproduce and verify fixes
- Validate acceptance criteria are met before release
- Participate in sprint planning to understand testing scope

### Goals
- Ensure high product quality and reliability
- Catch defects early in the development cycle
- Reduce production incidents through thorough testing
- Maintain comprehensive test coverage

### Typical Communication
- Daily standups to report testing progress and blockers
- Bug reports and test result summaries
- Collaboration with developers on defect resolution
- Sign-off communications before release

### Key Interactions
- **Developers**: Review acceptance criteria, reproduce bugs, verify fixes
- **Product Managers**: Clarify requirements and edge cases
- **Project Managers**: Report testing status and timeline impacts
- **Release Manager**: Provide test sign-off for releases

### Example Scenario
During a sprint, QA discovers that a new payment feature fails for international currencies. They document the defect with reproduction steps, work with developers to verify the fix, and re-test all payment flows before signing off on the release.

---

## UX Designer

### Role Summary
UX Designers research user needs, design intuitive interfaces, and ensure products deliver excellent user experiences. They bridge user requirements and technical implementation through design artifacts and usability validation.

### Responsibilities
- Conduct user research and usability studies
- Create wireframes, mockups, and interactive prototypes
- Define information architecture and user flows
- Establish and maintain design systems and patterns
- Validate designs through user testing and feedback
- Ensure accessibility and inclusive design practices
- Provide design specifications and assets to developers

### Goals
- Deliver intuitive, accessible user experiences
- Reduce friction in user workflows
- Align product design with user needs and business goals
- Maintain design consistency across the product

### Typical Communication
- Design reviews and critique sessions
- User research findings and recommendations
- Design specifications and handoff documentation
- Usability test reports and insights

### Key Interactions
- **Product Managers**: Collaborate on requirements, validate user needs, prioritize design improvements
- **Developers**: Provide design specifications, review implementation, clarify design intent
- **QA/Testing**: Validate usability and accessibility in testing, identify UX issues
- **Stakeholders**: Present design concepts, gather feedback, align on user experience goals
- **Project Managers**: Report design progress, coordinate design dependencies

### Example Scenario
A UX Designer conducts user interviews revealing that customers struggle with the checkout flow. They create prototypes of three alternative designs, test them with users, and work with the Product Manager to prioritize the most effective solution. The designer then collaborates with developers during implementation to ensure the design is implemented accurately and maintains accessibility standards.

---

## Release Manager

### Role Summary
Release Managers plan, coordinate, and execute production releases. They ensure all pre-release requirements are met, manage deployment activities, and communicate release status to stakeholders.

### Responsibilities
- Create and maintain release schedules and deployment plans
- Coordinate release activities across teams
- Verify all pre-release requirements are met (testing, documentation, approvals)
- Execute or oversee production deployments
- Monitor deployment health and coordinate rollback if needed
- Communicate release status and changes to stakeholders
- Maintain release documentation and runbooks
- Conduct release retrospectives

### Goals
- Ensure reliable, low-risk production releases
- Minimize deployment-related incidents and downtime
- Maintain clear communication throughout release process
- Continuously improve release processes

### Typical Communication
- Release schedules and deployment windows
- Pre-release readiness status reports
- Release notes and stakeholder announcements
- Post-release summaries and incident reports

### Key Interactions
- **Project Managers**: Align release schedules with project timelines, coordinate dependencies
- **Developers**: Verify code freeze, coordinate deployment artifacts, troubleshoot deployment issues
- **QA/Testing**: Obtain test sign-off, coordinate smoke testing during deployment
- **DevOps Engineer**: Collaborate on deployment automation, monitor system health
- **Security Lead**: Ensure security reviews complete before release
- **Stakeholders**: Communicate release plans, timelines, and outcomes
- **Product Managers**: Coordinate release content and prioritization

### Example Scenario
A Release Manager coordinates a major quarterly release involving three teams. They schedule deployment windows, verify that all teams have completed testing and security reviews, coordinate with DevOps to execute the staged rollout, monitor system metrics during deployment, and send stakeholder communications at each phase. When a minor issue is detected in staging, they work with developers to deploy a quick fix before proceeding to production.

---

## DevOps Engineer

### Role Summary
DevOps Engineers design and maintain CI/CD pipelines, automate infrastructure and deployments, and ensure system reliability. They enable teams to deliver software efficiently while maintaining high availability and performance.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines
- Automate build, test, and deployment processes
- Manage infrastructure as code and cloud resources
- Monitor system health, performance, and availability
- Implement and maintain security controls in pipelines
- Troubleshoot deployment and infrastructure issues
- Optimize deployment speed and reliability
- Maintain disaster recovery and backup systems

### Goals
- Enable fast, reliable automated deployments
- Minimize manual deployment work and human error
- Maintain high system availability and performance
- Continuously improve infrastructure efficiency

### Typical Communication
- Infrastructure status reports and incident updates
- Pipeline and automation documentation
- Capacity planning and cost optimization reports
- Collaboration on technical requirements

### Key Interactions
- **Developers**: Integrate build and test automation, troubleshoot pipeline issues, optimize build times
- **Release Manager**: Coordinate deployment execution, provide deployment tools and monitoring
- **Security Lead**: Implement security scanning in pipelines, ensure compliance controls
- **QA/Testing**: Automate test execution in CI/CD, provide test environment management
- **Project Managers**: Report infrastructure capacity and deployment capabilities
- **Product Managers**: Align infrastructure roadmap with product needs

### Example Scenario
A DevOps Engineer notices that deployment times have increased significantly. They analyze the CI/CD pipeline, identify bottlenecks in the test phase, and work with developers to parallelize tests and optimize docker image caching. They also implement automated smoke tests that run immediately after deployment, reducing the time Release Managers need to manually verify deployments. The improvements reduce deployment time from 45 minutes to 15 minutes.

---

## Security Lead

### Role Summary
Security Leads define security requirements, identify and remediate vulnerabilities, and ensure security best practices are followed throughout the development lifecycle. They serve as the primary security resource for teams and stakeholders.

### Responsibilities
- Define security requirements and standards for projects
- Review code, architecture, and deployments for security vulnerabilities
- Conduct threat modeling and security risk assessments
- Lead security incident response and post-incident reviews
- Provide security training and guidance to team members
- Maintain security tools and scanning infrastructure
- Coordinate security audits and compliance activities
- Track and remediate security vulnerabilities

### Goals
- Minimize security risks and vulnerabilities in products
- Build security awareness and capability across teams
- Ensure compliance with security policies and regulations
- Enable secure development practices without blocking delivery

### Typical Communication
- Security review reports and vulnerability assessments
- Threat model documentation
- Security incident reports and lessons learned
- Security training and best practice guidance

### Key Interactions
- **Developers**: Review code for security issues, provide secure coding guidance, verify vulnerability fixes
- **DevOps Engineer**: Implement security scanning in pipelines, configure security controls, review infrastructure security
- **Release Manager**: Provide security sign-off for releases, coordinate security-related release holds
- **Product Managers**: Define security requirements, assess security-related trade-offs, prioritize security work
- **Project Managers**: Report security status, coordinate security reviews in project timelines
- **QA/Testing**: Coordinate security testing, validate security fixes
- **All roles**: Respond to security incidents, provide security escalation point

### Example Scenario
During a security review, a Security Lead identifies that a new API endpoint lacks proper authentication. They document the vulnerability with severity and recommended fix, work with developers to implement OAuth2 authentication, and verify the fix through penetration testing. They also conduct a lunch-and-learn session for the team on common API security patterns. Before the release, they review the security scan results and provide sign-off to the Release Manager that all critical security issues are resolved.

---

## Stakeholders

### Role Summary
Stakeholders provide business context, requirements input, and decision-making authority. They represent various organizational interests and ensure projects align with business objectives.

### Responsibilities
- Provide business requirements and constraints
- Make or approve key project decisions
- Review progress and provide feedback
- Approve scope, timeline, and resource changes
- Communicate project needs to their organizations
- Participate in project reviews and gates

### Goals
- Ensure projects deliver business value
- Maintain alignment with organizational priorities
- Make informed, timely decisions
- Provide necessary support and resources

### Typical Communication
- Requirement gathering sessions and workshops
- Status updates and executive briefings
- Decision logs and approval communications
- Feedback on demos and deliverables

### Key Interactions
- **Project Managers**: Provide input on priorities, approve project plans, receive status updates
- **Product Managers**: Define success criteria, provide market/business context, review product direction
- **Release Manager**: Review release plans, approve deployment windows
- **All roles**: Available for questions and approvals during project execution

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understanding role interactions helps clarify handoffs, accountability, and collaboration patterns.
- These personas support onboarding by making responsibilities and communication expectations explicit.

