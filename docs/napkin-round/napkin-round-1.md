Napkin Round 0 Market Match

1. Shape

Market Match is a web-based market research platform that is being transformed from a vibe-coded startup application into a secure, scalable, API-first, white-label enterprise platform.

Main components:

- Frontend / interactive swipe-based survey interface
- Backend and API layer
- Database and analytics
- Authentication, authorization, and tenant management
- White-label and external system integrations

2.  The Hard Part

The hardest part is modernizing the existing vibe-coded application without breaking the functionality that already works.

The current application was developed quickly to test the product with real users. Now the team must understand the existing codebase, identify technical debt, and determine what should be documented, refactored, redesigned, or rebuilt.

This becomes more difficult because Version 3 must eventually support multiple organizations, APIs, security, white-label customization, analytics, and enterprise-scale usage.

3. Bottleneck

The first bottleneck will likely be understanding and modernizing the existing codebase as a six-person team.

If the current vibe-coded application has unclear architecture, limited documentation, or tightly connected components, team members may have difficulty determining how changes affect the rest of the system. This could slow development and cause bugs or integration problems.

A second scalability bottleneck may appear in the database/API architecture when many organizations and users begin using the platform simultaneously.

4. Stack

We would initially continue with the existing Market Match technology stack rather than immediately replacing it.

The team should first inspect the current frontend, backend, database, APIs, authentication, deployment, logging, and monitoring. After understanding the current architecture, we can determine which technologies should remain and which components need to be refactored or replaced.

5. Kill Risks

Risk 1 Existing Codebase

Because the current application was rapidly vibe-coded, parts of the codebase may lack consistent architecture or documentation. If dependencies between components are unclear, changing one part of the application could unexpectedly break another.

Risk 2 Multi-Tenant Data Isolation

Version 3 needs multiple organizations to use the same Market Match infrastructure while keeping their users, surveys, configurations, and data separate. If organization-level authorization is implemented incorrectly, one organization's data could become accessible to another organization.

Risk 3 Enterprise Scope

Version 3 includes scalability, APIs, white-label functionality, analytics, security, authentication, monitoring, database improvements, and other enterprise features. If the team attempts to fully implement all of these at once, the project could exceed what the team can complete within two semesters.

6. Verdict

Yes, the project is feasible for the team if development is divided across the two semesters and the scope remains focused.
Semester One should focus on understanding and documenting the existing system, identifying technical debt, designing the Version 3 architecture, developing the API and security strategy, and building an initial prototype.
If scope needs to be reduced, we would postpone lower-priority advanced features and integrations rather than trying to rebuild the entire application.
The core priority should be establishing a secure, scalable, multi-tenant and API-first foundation that Market Match can continue developing after the senior design project.
