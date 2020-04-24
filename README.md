# Meditation App

## Description

Meditation app / web app with various functions related to meditation. The user should be able to enter various inputs both for their current mood and their goals. Then he receives a personalized offering of programs that are available to him. Upon choice, he receives access to daily tasks and guided meditations (audio).

## Architecture

- App (native / web) zur Interaktion mit dem User
- REST Api
- Diverse Microservices (z.B. UserService, OfferingService, etc.)
- DB: Users (PostgreSQL), Offerings (MongoDB)

## Technology Stack

- Frontend App: Flutter
- REST Api & Webservices: Spring Boot
- VCS: GitHub
- GitOps: Argo
- Container: Docker
- Clustering: Kubernetes / Openshift
- Cloud: TBD

## Codebase

- Monorepo
- Modules: [main], [client], [api], [microservice_xy]

## Release

- Versioning: MAJOR.MINOR.PATCH
- MAJOR: making incompatible API changes
- MINOR: adding functionality in a backwards-compatible manner
- PATCH: making backwards-compatible bug fixes