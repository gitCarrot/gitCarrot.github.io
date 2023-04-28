---
layout: essay
type: essay
title: "To Build Good Design Pattern"
# All dates must be YYYY-MM-DD format!
date: 2023-04-27
published: true
labels:
  - Design Pattern
  - Project
  - Clean Code
---

Design patterns can be compared to building blocks in architecture. Just as architects use a set of standard building blocks to construct a building, programmers use design patterns as a foundation for their code. These building blocks, or patterns, provide a solid framework for creating efficient and effective code. They are not specific solutions, but rather a set of guidelines that can be adapted to meet the unique requirements of a project.

In the Manoa Link project, I have used design patterns to make the code scalable and maintainable. The platform has three different user roles - student, company, and admin - and each role has a unique interface. To manage this complexity and keep the code organized, I employed the Model-View-Controller (MVC) design pattern. This pattern allowed me to separate the code into three distinct parts - the model, which manages the data, the view, which presents the data to the user, and the controller, which handles user input and updates the model. This structure helps to ensure that changes in one part of the code do not affect the others, making it easier to maintain and update the platform over time. Additionally, to avoid duplicated code in the tags used for filtering events and companies, I implemented the Singleton design pattern. This pattern ensures that there is only one instance of the tag code, making it more efficient and reducing the risk of bugs.
