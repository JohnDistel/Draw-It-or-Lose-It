# Draw It or Lose It  
## CS 230 - Module Eight Journal  
### Software Design Portfolio Reflection  

**Project:** The Gaming Room – GameAuth Application  

---

## Summary and Software Requirements  

The client, The Gaming Room, requested a web-based game service that supports multiple teams and players while ensuring each game instance remains unique. The system needed to follow object-oriented principles, enforce uniqueness constraints for games, teams, and players, and support RESTful communication through HTTP endpoints. It also had to be scalable and capable of operating across different platforms.

To meet these requirements, I designed a structured object-oriented system, applied the Singleton pattern to manage a single game service instance, and organized the architecture to support scalability and maintainability.

---

## What I Did Well  

I effectively translated client requirements into clear technical decisions. I justified the use of design patterns, particularly the Singleton pattern, and explained how architectural choices supported scalability and platform flexibility. The UML diagrams and defined class relationships made the system structure clear and logical.

---

## How the Design Document Helped  

Creating the design document before coding clarified class responsibilities and system constraints. It reduced rework and served as a blueprint during implementation of the REST services. Identifying constraints such as name uniqueness early helped prevent logical errors later in development.

---

## One Area to Improve  

If revising the document, I would expand the scalability and deployment discussion. While platform considerations were addressed, deeper analysis of cloud deployment, database integration, or long-term growth strategies would strengthen the design.

---

## Interpreting User Needs  

I translated high-level requirements into enforceable system constraints, such as ensuring game name uniqueness at the service level. Considering user needs during design is essential because it ensures the software solves the intended problem rather than simply functioning correctly.

---

## My Design Approach  

My approach involved analyzing requirements first, mapping constraints to object-oriented structures, and selecting appropriate design patterns. In future projects, I would continue using UML modeling and structured requirement analysis, while incorporating clearer acceptance criteria to further align development with client expectations.
