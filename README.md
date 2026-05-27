# Spring Boot — Codecademy Intro

Part of the **[Learn Spring](https://www.codecademy.com/learn/learn-spring)** course on Codecademy.

This is my first ever Spring Boot project. The goal was purely to get comfortable with the framework: initializing a project with Spring Initializr, understanding the project structure, and getting a simple HTTP endpoint running.

## What it does

Exposes a single GET endpoint:

```
GET /helloworld
→ "Hello World!!!!! the skies the limit!!!!"
```

## Stack

- Java 25
- Spring Boot 4.0.6
- Spring Web MVC

## Running locally

```bash
./mvnw spring-boot:run
```

Then visit `http://localhost:8080/helloworld` in your browser.

## Context

This project is part of my broader Spring learning path as I prepare for a Java/Spring backend apprenticeship at JPMorgan Chase. It's intentionally minimal — just enough to understand how Spring bootstraps an application and how `@RestController` wires up an HTTP route.
