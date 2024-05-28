# Backend Orchestration

Backend orchestration can be vital in certain web application scenarios, particularly in critical situations that require seamless coordination and management of various backend services. Focusing on the critical aspects of the application, it's easy to understand that it's essential to prioritize resources, handle peak loads, and ensure fault tolerance, ultimately leading to a more robust and responsive application.

## QRMeat critical case

After much thought into what might justify the deployment of backend orchestration in the QRMeat application, we came to the conclusion that there was one scenario where it made a lot of sense. This scenario involves the workflow of inserting a review, where it's crucial to ensure the validity of our review data. We don't want the possibility of an unsatisfied customer deploying a bot to leave millions of bad reviews on a product just because they had a bad experience. As a way of validating user input and preventing corruption of review data, we proposed the use of a third-party service like reCAPTCHA from Google to ensure the input is human before inserting a review.

## Backend Orchestration Diagram
<p align = "center ">
<img src="./assets//BE_Orchestration-dark.png#gh-dark-mode-only" alt="Backend Orchestration" />
<p\>

<p align = "center ">
<img src="./assets/BE_Orchestration-light.png#gh-light-mode-only" alt="Backend Orchestration" />
<p\>

#### [Back to Backend](../README.md)
