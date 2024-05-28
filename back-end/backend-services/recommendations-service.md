# Backend Recommendations Service ADR

## Status

[Proposed]

## Context

The backend Recommendations Service division, surged from the architectural principle of spliting the backend into business oriented services. 

## Description

This service implements recommendation systems to recommend specific entities, on this application it's used for the recommendation of Products and News Articles.

## Resources

Recommendations are used by the app to populate "Featured Products" sections and also provide "Featured" Articles.

## REST API

<img src="../requests/assets/RecommendationsService.png" alt="REST Recommendations Service" />

## Business Objects Interaction


<img src="../business-objects/assets/RecommendationsBOs.png" alt="Business Objects Interaction"  />


#### [Back to Backend Services](./README.md)
#### [Back to Backend](../README.md)
