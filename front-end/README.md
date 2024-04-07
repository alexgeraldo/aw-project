# Introduction:
In the subject of Web Applications lectured by professor Pedro Antunes in the Faculty of Sciences of the University of Lisbon, students Nuno Marques and Alexandre Geraldo were challenged with developing a Frontend Blueprint for QRMeat, a mobile application. QRMeat’s key feature is enabling users to quickly access  information about meat products via QR codes, including sustainability, processing details, nutritional value and user feedback.

# Decision:
## Embracing Business-Oriented Micro-Frontends


As modern web development keeps evolving, the quest for scalable and maintainable design solutions is becoming a standard. This frontend blueprint aims to integrate the development of the QRMeat app in the modern landscape of web development, focusing on delivering scalable and maintainable design choices, meeting the dynamic needs of users and businesses alike. The traditional monolithic architectures while effective in certain scenarios, have been proved to face many challenges when it comes to flexibility, agility and scalability. So by recognizing these limitations, the decision to adopt a micro-frontends architecture emerged as a strategic choice for our project.

We chose a Business Oriented selection of micro-frontends as it facilitates the division of the teams assigned to each micro-frontend so each one can be treated as an internal business promoting internal motivation on the development of each micro-frontend. This approach as mentioned before as in mind the reusability and maintainability aspects, micro-frontends enable us to encapsulate functionality within units that can be reused across different parts of the application, minimizing redundancy  and simplifying future maintenance and troubleshooting.


# Micro-Frontends:

  - [Authentication and Account Management](./micro-frontends/authentication.md)
  - [Catalog](./micro-frontends/catalog.md)
  - [News and Statistics](./micro-frontends/news.md)
  - [Generic Elements (not a Micro-Frontend)](./micro-frontends/generic_elements.md)


# Stories:
  - [An Animal Tale (Check Product Story)](./stories/check-product-story.md)
  - [A Hero's Voice (Give Feedback Story)](./stories/give-feedback-story.md)
  - [A Journey Through the Headlines (Check News Story)](./stories/check-news-story.md)
  - [An Eye on Progress (Check Statistics Story)](./stories/check-statistics-story.md)
  - [Through the Gateway (Authentication Story)](./stories/authentication_story.md)


# Frontend Orchestration:
  - [Catalog Frontend](./orquestration/catalog-orquestration.png)
  - [News and Statistics Frontend](./orquestration/news-statistics-orquestration.png)
  

# Narrative Arc:
  - [QR Meat Narrative Arc](narrative-arc.png)
  - [QR Meat Narrative Arc .svg (Light Download Version)](narrative-arc.svg)

