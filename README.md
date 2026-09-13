# E-Commerce Microservices

A .NET-based e-commerce backend project structured around **microservice architecture**, with separate services, shared components, gateways, identity management, and frontend applications.

## Architecture

The repository is organized around the following major areas:

- `Services/` — domain-focused microservices
- `Gateways/` — API gateway layer
- `IdentityServer/` — authentication and identity infrastructure
- `Shared/` — reusable shared components
- `Frontends/` — client-facing applications
- `ECommerceMicroservices.sln` — main Visual Studio solution

## Tech Stack

- .NET / C#
- ASP.NET Core
- Microservices
- API Gateway pattern
- Identity / authentication infrastructure
- Shared libraries
- Multi-project solution architecture

## What This Project Demonstrates

- Separating an application into domain-oriented services
- Working with a multi-project .NET solution
- Centralized identity and authentication
- API gateway-based request routing
- Shared infrastructure across services
- Frontend/backend separation
- Building a foundation for independently deployable services

## Getting Started

1. Clone the repository.
2. Open `ECommerceMicroservices.sln` in Visual Studio, Rider, or another compatible .NET IDE.
3. Review `Ports.txt` for the ports used by the services.
4. Configure each service's local settings and dependencies.
5. Start the required infrastructure and services for the workflow you want to test.

Because this is a multi-service solution, individual services may require their own database, message broker, identity, or application configuration.

## Repository Structure

```text
ECommerceMicroservices.sln
Frontends/
Gateways/
IdentityServer/
Services/
Shared/
Ports.txt
```

## Development Notes

This repository is part of my work on backend architecture and distributed application design. Before using a similar architecture in production, areas such as secrets management, container orchestration, CI/CD, observability, resilience, automated testing, and deployment configuration should be reviewed carefully.

## Repository Hygiene

IDE-specific files such as `.vs/` should normally be excluded from source control. A clean `.gitignore` helps keep the repository focused on source code and configuration that belongs to the project.

## About

This project is part of my backend-development portfolio and focuses on practical experience with .NET microservices and service-oriented architecture.

Developed by **Ali Gökçe**.
