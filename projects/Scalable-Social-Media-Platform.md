---
layout: project
type: project
image: img/social-media.jpg
title: "Scalable Social Media Platform"
date: 2023-2-1
published: true
labels:
  - Spring Boot(gradle)
  - Spring Boot Security (JWT)
  - JPA
  - PostgreSQL
  - Redis
  - Kafka
  - TDD
summary: "Scalable Social Media Platform using Spring Boot, JWT, Redis, and Kafka"
---

<!-- <div class="text-center p-4">
  <img width="400px" src="../img/reddit.png" >
</div> -->
<br><br>

## Abstract:
This project aims to develop a scalable social media platform that leverages the Spring Boot framework, JSON Web Tokens (JWT), Redis caching, and Kafka for asynchronous data processing. The platform will provide key features such as user authentication, post creation, editing, deletion, feed display, and additional functionalities including likes, comments, and notifications.

## Introduction:
The ever-growing demand for social media platforms has led to the need for highly scalable and efficient applications that can handle large amounts of traffic. This project aims to create a simple yet powerful social media application that addresses these challenges using popular technologies and tools. The following sections outline the major components, features, and technologies utilized in this project.

## User Authentication
The application uses Spring Boot Security and JWT for user registration and authentication. JWT provides a secure and stateless way to handle user authentication and authorization, ensuring data integrity and security.

## Core Features
The platform offers a range of social media functionalities, including:

 ## - 2.1. Post Creation, Editing, and Deletion: Users can create, edit, and delete their own posts. (Progressing)
 - 2.2. Feed Display: A feed system that displays the latest posts from users in a user's network.
 - 2.3. Likes, Comments, and Notifications: Users can interact with posts by liking and commenting, and receive notifications for these actions.

## Scalability and Performance
To handle large-scale traffic and improve performance, the application incorporates the following optimizations:
 - 3.1. Redis Caching: The platform uses Redis to cache frequently accessed data, reducing latency and improving user experience.
 - 3.2. Server-Side Events: The application employs server-side events to enable real-time updates for likes, comments, and notifications.
 - 3.3. Kafka for Asynchronous Data Processing: Kafka is utilized for handling asynchronous data processing, ensuring smooth performance under heavy load.

## Conclusion:
The proposed social media platform demonstrates a scalable and efficient solution that combines the power of Spring Boot, JWT, Redis, and Kafka. By incorporating these technologies, the application is well-equipped to handle large-scale traffic and provide users with a seamless and interactive experience. Future enhancements may include additional features such as direct messaging, user profiles, and advanced search capabilities.

<br><br><br>

Repo Url : [Social Media Project](https://github.com/gitCarrot/Social-Media-Project)
