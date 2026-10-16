> 📚 **Coursework labs (fork)**
>
> This repository is a fork of
> [nebyatweb/cs545-waa-assignments](https://github.com/nebyatweb/cs545-waa-assignments),
> a set of CS545 Web Application Architecture course labs. All code was written by the
> original author (Nebyat Tibebu) and is licensed under the [Apache License 2.0](LICENSE).
> Original README title: `cs545-waa-assignments`.

# Web Application Architecture Project

A progressive series of nine labs that build a posts-and-comments application,
first as a Spring Boot back end and then as a React front end.

## Contents

| Folder | What it covers |
|---|---|
| `labs/lab1` | Spring Boot REST API for posts with a layered controller → service → repository design |
| `labs/lab2` | Users and posts with Spring Data JPA and DTO mapping |
| `labs/lab3` | Users, posts, and comments with JPA relationships |
| `labs/lab4` | Spring AOP for logging and execution-time tracking |
| `labs/lab5` | Spring Security with JWT authentication |
| `labs/lab6` | First React application (React 18) |
| `labs/lab7` | React components and a posts dashboard |
| `labs/lab8` | Post details, comments, and a new-post form using Axios |
| `labs/lab9` | Client-side routing with React Router v6 |

## Tech Stack

Java · Spring Boot 2.6 · Spring Data JPA · Spring AOP · Spring Security · JWT · React 18 · Axios · React Router · Maven

## Running

- **Back end (labs 1–5):** `cd labs/labN && ./mvnw spring-boot:run`
- **Front end (labs 6–9):** `cd` into the lab's React folder, then `npm install && npm start`
