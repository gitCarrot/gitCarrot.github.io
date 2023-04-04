---
layout: project
type: project
image: img/gps.png
title: "Recommend Service for pharmacy"
date: 2023-01-09
published: false
labels:
  - Spring Boot
  - Spring Retry
  - JPA
  - Redis
  - BootStrap
  - Docker
summary: ""
---

<div class="text-center p-4">
  <img width="400px" src="../img/shortestPath.jpg" class="img-thumbnail" >
  <img width="400px" src="../img/pharmacy.jpg" class="img-thumbnail" >
</div>

It is a spring boot project for pharmacy recommendation service by utilizing external API and public data. The user enters the address, and recommends the pharmacy closest to the input address. Only pharmacies within a specified radius are recommended using the formula for obtaining the shortest distance between two points in a spherical surface. The external API currently uses Korea's Kakao Address Search API, but it will be replaced by Google Address Search API, and public data will also be changed to Hawaiian data. Since the pharmacy domain data is not large, the caching function of redis will not be very helpful, but the performance was improved by caching the part that inquires pharmacy data in database and returning the result value after calculating the distance in every request.

Function implemented
- Address retrieval using external api.
- Find the distance between the two latitude coordinates with the haversine formula.
- Improve performances by caching infrequently updated data by redis
- Use map api to show directions with nearby pharmacy information.


Used Stacks
  - Spring Boot
  - Spring Retry
  - JPA
  - Redis
  - BootStrap
  - Docker

<br><br><br>
Repo URL : update soon





