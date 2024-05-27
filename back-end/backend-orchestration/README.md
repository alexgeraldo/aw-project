# Backend Orchetration

Backend orchestration can be vital in certain web application scenarios, critical scenarios may need to ensure seamless coordination and management of various backend services. Focusing on the critical aspects of the application it's easily understadable that it's essential to prioritize resources, handle peak loads and ensure fault tolerance, ultimately leading to a more robust and responsive application.

## QRMeat critical case

After much tought into what might justify the deployment of a backend orchestration on the QRMeat application we came to the conclusion that there was one scenario where it made alot of sense.
This is the workflow of introducing a review, we should ensure the validity of our review data. We don't want the possibility of having an unsatisfied customer deploying a bot to leave milions of bad reviews on a product just because he had a bad experience. As a way of validating user input and preventing corruption of review data we proposed the use of a third-party service like reCAPTCH from Google to ensure the input is human before introducing a review.

## Backend Orchestration Diagram
<p align = "center ">
<img src="./assets/BEOrchestration_dark.png#gh-dark-mode-only" alt="Backend Orchestration" />
<p\>

<p align = "center ">
<img src="./assets/BEOrchestration_light.png#gh-light-mode-only" alt="Backend Orchestration" />
<p\>

#### [Back to Backend](../README.md)