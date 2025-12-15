# CS 230 Operating Platforms Portfolio

## Project Overview

The client for this project was The Gaming Room, a company that developed the game Draw It or Lose It and wanted to expand it beyond its original Android-only platform. The client’s goal was to redesign the software architecture so the game could be delivered as a web-based application capable of supporting multiple teams and players across different operating systems and devices. The system needed to enforce unique game and team names, maintain a consistent and centralized game state, and be scalable for future growth as the user base increases.

The software design focused on creating a platform-independent solution that could run reliably in a distributed environment. By separating core game logic from client interfaces, the design allows users on Windows, macOS, Linux, and mobile devices to access the game through a browser while relying on a centralized backend service to manage all game data and rules.

## Reflection

One area I did particularly well in developing this documentation was analyzing and comparing operating platforms and clearly justifying my recommendations. I evaluated Windows, macOS, Linux, and mobile platforms in terms of performance, memory management, security, and scalability. Based on this analysis, I recommended Linux as the primary server platform and explained the reasoning in a way that could be understood by both technical developers and nontechnical stakeholders. This helped ensure that architectural decisions were well supported and clearly communicated.

Working through the design document was especially helpful in understanding how the system should be structured before any code was written. Creating the domain model and defining responsibilities for entity classes and services made it easier to visualize how data flows through the application. This process reinforced the importance of separating concerns and designing with scalability and maintainability in mind, which reduces errors and confusion during implementation.

If I could revise one part of my work, I would expand the UML explanations by adding more detailed interaction examples, such as how a game session progresses from creation to completion. Including additional sequence-level detail would make the document even more useful as a long-term reference during development or onboarding of new team members.

User needs were interpreted by focusing on accessibility, reliability, and consistency across platforms. Since players may access the game from different devices and operating systems, the design emphasizes a centralized server model with thin, browser-based clients. Considering user needs is critical because a technically correct system will still fail if it does not provide a consistent, reliable, and accessible experience for its users.

My approach to designing software involved careful requirements analysis, evaluation of operating platforms, and structured object-oriented design using established design patterns. In the future, I would continue using this approach along with iterative reviews, UML modeling, and early stakeholder feedback. These strategies help ensure that software designs align with user expectations, business goals, and long-term maintainability.
