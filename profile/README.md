# Introduction

A series of personal projects/products using the brand name JTM-Network. The aim of these projects is to solve business problems, using microservice architecture, to split the problems into sub-problems and to be integrated into the Kubernetes Cluster without affecting current processes & offers scalability. Most services used in the Network are public as to show how we solve these problems.

## Table contents
- [Preliminary Questions](#preliminary-questions)
- [Technologies](#technologies)
- [Microservices](#microservices)

## Preliminary Questions

### What do we aim to solve?

Minecraft plugins offer a solution to server owners by providing a unique experience to their users without the need to install anything themselves and being accessible by a vanilla Minecraft launcher. It takes considerable time for a plugin developer to think of ideas and create them, and they will often set a price for the plugin they create. The problem is, what is to stop someone from paying for the work and sharing it freely somewhere else, circumventing all the time the developer has spent working to create a unique idea. What we aim to do is provide authentication against this by making sure the server owner using the plugin has actually paid for that plugin and disabling the plugin if not. We aim to help the plugin developers protect their work, as without their ingenuity, Minecraft wouldn’t have longevity.

### Using Kotlin over Java?

There aren't many differences between the languages other than Kotlin being more functional and less verbose, and those are big reasons why I chose Kotlin. From experience I was writing 25-35% less lines of code in Kotlin than in Java for the same feature due to writing less words. With the knowledge of Design Patterns, OOP paradigms & SOLID principles being transferable, it makes Kotlin a great language to use for faster development. IntelliJ also offers a way to convert Kotlin code to Java code and vice versa, which makes it very versatile to use in current Java projects.

## Microservices
- auth0-gateway-service (Private due to security reasons)
- [plugin-service](https://github.com/JTM-Network/minecraft-service)
- [version-service](https://github.com/JTM-Network/minecraft-service)
- [payment-service](https://github.com/JTM-Network/payment-service)
- [profile-service](https://github.com/JTM-Network/profile-service)

## Technologies

### Languages:
- [Java](https://www.java.com/en)
- [Kotlin](https://kotlinlang.org)
- [JavaScript](https://www.javascript.com)
- HTML/CSS

### Frameworks:
- [Spring Boot](https://spring.io/projects/spring-boot)
- [Spring Webflux](https://docs.spring.io/spring-framework/docs/current/reference/html/web-reactive.html)
- [VueJS](https://vuejs.org/)
- [NuxtJS](https://nuxtjs.org/)

### Dev Ops:
- [Docker](https://www.docker.com/)
- [Kubernetes](https://kubernetes.io/)
- [Github Actions](https://github.com/features/actions)
- [Google Cloud Platform](https://cloud.google.com/)

### Databases:
- [MongoDB](https://www.mongodb.com/)
- [Cassandra](https://cassandra.apache.org/_/index.html)
- [Redis](https://redis.io/)
- [SQL](https://en.wikipedia.org/wiki/SQL)
