# Backend

In the subject of Web Applications lectured by professor Pedro Antunes in the Faculty of Sciences of the University of Lisbon, students Nuno Marques and Alexandre Geraldo were challenged with developing a Backend elements for QRMeat, a mobile application. QRMeat’s key feature is enabling users to quickly access information about meat products via QR codes, including sustainability, processing details, nutritional value and user feedback.

# Motivation

In developing QRMeat, we prioritized decisions that promoted a modular and maintainable backend architecture to ensure a robust and responsive performance for the application. We divided backend tasks into distinct business-oriented services, enhancing modularity, reusability, flexibility and testability. By defining high-level business objects (BOs) that encapsulate complex logic efficiently, we achieved simplicity and data independence which can prove crucial for seamless integration and isolated unit testing. We also followed Pragmatic REST principles, aiming to create intuitive APIs with single resources per service, cohesive request sets, and atomic operations, ensuring ease of use, security and efficiency. This structured approach allows us to prioritize resources and ensure fault tolerance contributing to the delivery of a responsive and stable application. As we started by developing the Frontend, the workflows of the backend (stories) have been integrated with the frontend and directly applied on the App Blueprints.

# Backend Services:
   #### [Full Page Here](./backend-services/README.md)

  <!-- - [Authentication and Account Management](./micro-frontends/authentication.md) -->
  - [Market Service](./backend-services/market-service.md)
  - [Product Service](./backend-services/product-service.md)
  - [Reviews Service](./backend-services/reviews-service.md)
  - [Statistics Service](./backend-services/statistics-service.md)
  - [News Service](./backend-services/news-service.md)
  - [Likes Service](./backend-services/likes-service.md)
  - [Recommendations Service](./backend-services/recommendations-service.md)
  - [Authentication Service](./backend-services/authentication-service.md)
  - [Users Service](./backend-services/users-service.md)
  
# Requests
   #### [Full Page Here](./requests/README.md)

  - [Market Service API](./requests/MarketService-API.md)
  - [Product Service API](./requests/ProductService-API.md)
  - [Reviews Service API](./requests/ReviewsService-API.md)
  - [Statistics Service API](./requests/StatisticsService-API.md)
  - [News Service API](./requests/NewsService-API.md)
  - [Likes Service API](./requests/LikesService-API.md)
  - [Recommendations Service API](./requests/RecommendationsService-API.md)
  - [Authentication Service API](./requests/AuthenticationService-API.md)
  - [Users Service API](./requests/UsersService-API.md)

# Business Objects (Backend Services Data)
   #### [Full Page Here](./business-objects/README.md)

    (FALTA HIPERLINKS PARA TABELAS COM BOs DATA)
  - [[Market]](./business-objects/MarketBO.md)
  - [[Product]](./business-objects/ProductBO.md)
  - [[Review]](./business-objects/ReviewBO.md)
  - [[Article]](./business-objects/ArticleBO.md)
  - [[Statistics]](./business-objects/StatisticsBO.md)
  - [[User]](./business-objects/UserBO.md)


# Backend Orchestration
   #### [Full Page Here](./backend-orchestration/README.md)
<p align = "center ">
<img src="./backend-orchestration/assets/BEOrchestration_dark.png#gh-dark-mode-only" alt="Backend Orchestration" />
<p\>

<p align = "center ">
<img src="./backend-orchestration/assets/BEOrchestration_light.png#gh-light-mode-only" alt="Backend Orchestration" />
<p\>


# Full API Specification (Swagger file)

 #### [Here](./api-specification.yaml)



#### [Back to Repository Menu](../README.md)


