# Authentication Micro-Frontend ADR

## Status

[Proposed]

## Context

The QRMeat project aims to develop a comprehensive application prototype tailored to the meat industry, catering to various functionalities crucial for both consumers and industry professionals. The primary focus is on providing users with a seamless experience in accessing information about markets, types of meat, and detailed product insights encompassing nutrition data and the comprehensive history of the product, tracing back to the creation of the animal it originated from.

Additionally the QRMeat app also provides users with news related to the meat industry and provides statistical information concerning statistical metrics such as sustainability and animal well being.

The Authentication Micro-Frontend is one important component that is dedicated to user authentication, managing application preferences, and handling user account settings.

## Decision

Decomposing the QRMeat prototype using Business Oriented Decomposition was decided to make authentication and user-related features a single micro-frontend inside the application.

This decision aims to promote reusability and streamline development processes by creating a more generic solution that can be easily integrated into multiple applications. By centralizing customer data management and authentication processes, the project not only enhances scalability but also lays the groundwork for future expansions into diverse domains beyond the meat industry and the QRMeat application.

## Consequences

[Outline the potential positive and negative impacts of the decision, including how it affects views, components, frontend services, and resources. Consider aspects such as performance, scalability, maintainability, team workflow, and dependencies.]

### Views

- [List the views affected by this decision and describe any changes needed in each view.]

### Components

- [List the components affected by this decision and describe any changes needed in each component.]

### Frontend Services

- [List the frontend services affected by this decision and describe any changes needed in each service.]

### Resources

- [List any resources affected by this decision, such as libraries, frameworks, or third-party tools, and describe any changes needed.]

## Alternatives

[Describe alternative options that were considered and why they were not chosen. This helps provide context for the decision and can be helpful for future reference.]

## References

[Include any relevant links, documents, or discussions that informed this decision. This could include architectural diagrams, research papers, or discussions within the team or community.]

