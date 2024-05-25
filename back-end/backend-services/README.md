<!-- # Authentication Micro-Frontend ADR

## Status

[Proposed]

## Context and Problem Statement

Our small team is developing a new meat related app called QR Meat that allows to check on meat products and related information. We need to decide on how we are going to divide the in terms of Micro-frontends to ensure requirements such as modularity, reusability, flexibility, testability and maintainability.

## Decision Drivers

- Dividing the overall app into business separated blocks, using decomposition by "Business Capabilities".
- Ensure the ability to change the frontend without affecting other business areas, promoting modularity, flexibility and maintainability.
- Stimulate feature development having dedicated teams for specific business areas.
- Facilitate testing and deployment by isolating different components.
- Promote frontend component reusability in other projects or in selling as a standalone solution for third-parties.

## Decision Outcome

We decided based on the listed drivers to aggregate all the views, components and services related to user authentication, management and preferences under a single "Authentication Micro-Frontend". This way there will be a team dedicated to support and develop the features related with this frontend and this will promote specially flexibility, maintainability and reusability. This way Authentication related features can be reused in future projects or can be sold as a standalone solution for third-parties. Also important to mention, that this way the authentication system can be centralized/reused for all the "company" apps and services.

### Views, Components, FE Services -->


# The Backend Services

## Context

Our small team is developing a new meat related app called QR Meat that allows to check on meat products and related information. We need to decided to organize and devide backend tasks into business oriented services as way to ensure modularity, reusability, flexibility, testability and maintainability. We came up with a total of 9 services that proved crutial for the seamless function of the application. 

## Decision Drivers

- Dividing the overall app into business separated blocks, using decomposition by "Business Capabilities".
- Maximize the ability to change the backend services without affecting other business areas, promoting modularity, flexibility and maintainability.
- Facilitate testing by having development teams dedicated to specific business areas (services).
- Promote services reusability in other projects/applications aswell as selling them as a standalone solution for third-parties.


## Backend Services 
  - [Auth Service](.auth-service.md)
  - [Likes Service](.likes-service.md)
  - [Market Service](.market-service.md)
  - [News Service](.news-service.md)
  - [Product Service](.product-service.md)
  - [Recommendations Service](.recommendations-service.md)
  - [Reviews Service](.reviews-service.md)
  - [Statistics Service](.statistics-service.md)
  - [Users Service](.users-service.md)


## Diagram

<!-- Fazer o diagrama que mostra todos os BE Services a interagir uns com os outros -->


## Backend Services Table
<!-- INSERIR A TABELA TASK 6 AQUI -->
<!-- und dev -->



