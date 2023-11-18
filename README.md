
# react-micro-frontend

## **What are micro frontends?**

Micro frontends are an architectural design approach to frontend web development. The frontend app is decomposed into self-contained modules or features that are loosely connected and semi-independent. They can be owned by different frontend teams and deployed separately from other features. The concept is inspired by microservices.

## **How is micro frontend architecture implemented?**

Micro frontend architecture is implemented by breaking down a frontend application into smaller, loosely coupled modules or functions. These modules communicate through well-defined APIs or events. To implement micro frontends in a monolithic app, begin by identifying decouplable features. Extract and refactor these features into separate codebases with their own build and deployment processes. Establish communication between the micro frontends and create a shell as their entry point. Gradually migrate and integrate the micro frontends into the shell application.

## **When would you use a micro frontend architecture?**

It is most beneficial to apply a micro frontend architecture approach with large and complex applications when you are trying to achieve team autonomy, technology diversity, and scalability.

## **What is a micro UI?**

A micro UI, or micro user interface, is a small, self-contained user interface component that can be developed and deployed independently. It is typically used within the context of micro frontend architecture to represent a specific part or feature of a larger application. Micro UIs are designed to be modular, and reusable, and can communicate with other micro UIs or components to create a cohesive user experience.


**In this example I demonstrated React Micro Frontend using Wepback.**