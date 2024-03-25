# Catalog Micro-Frontend

## Context
The catalog micro-frontend is responsible for numerous and various functionalities, all connected to the displaying of products 
and the respective supermarket selection.

## Decision

The decision to choose a catalog focused micro-frontend was business focused, but besides that it was intuitive since there are numerous 
views on the QR meat app related to catalog functionality, there are some other functionalities associated with this micro-frontend besides 
cataloging but these are functionalities make sense to be developed on pair with the catalog and by the same team to ensure a seamless 
user experience, promoting a scalable solution with the possibility of later added functionality for different scenarios outside the 
QRMeat application.

## Consequences 

Developing a Catalog focused micro-frontend involves several benefits, but not without some drawbacks.

### Benefits
  - Modularity for Scalability: by developing market specifit features that can be developed, deployed and scaled independently.
  - Autonomously focused development teams: having teams focused on a specific functionality promotes faster development cycles, as teams can
work independently without waiting for coordination with other teams while also promoting innovation as teams have the freedom to experiment
with new features or technologies within their micro-frontend.
  - Reusability of components: the micro-frontend approach encourages the reuse of UI components across different parts of the application. Components like
searchbars or cards can be developed onece and shared across multiple micro-frontends. Although this is not the case with QRMeat it's stil to be considered
as a benefit as we do not know if components from the Catalog Micro-Frontend might be reusable on future versions of the app with added functionality.
  - Fault Isolation: 

  - (under editing) ...
  -
  

## Views

[List the views affected by this decision and describe any changes needed in each view.]

(what should I name the views ??? ) or should I just add some images to the .md to show which views belong to the
catalog micro-frontend ( I think it makes more sense to add an image and elaborate on them) talking about the components and the
frontend services as well as the resources needed to make these work. (ask Alex)


### Components

[List the components affected by this decision and describe any changes needed in each component.]

### Frontend Services

[List the frontend services affected by this decision and describe any changes needed in each service.]

### Resources

[List any resources affected by this decision, such as libraries, frameworks, or third-party tools, and describe any changes needed.]

## Alternatives

[Describe alternative options that were considered and why they were not chosen. This helps provide context for the decision and can be helpful for future reference.]


## References

[Include any relevant links, documents, or discussions that informed this decision. This could include architectural diagrams, research papers, or discussions within the team or community.]






