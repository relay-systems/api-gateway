# api-gateway

API gateway of Relay: the single entry point for clients, routing requests to the backend services.

**Status:** not implemented yet. This repository only holds the project setup.

## Planned stack

Java 21 and Spring Cloud Gateway. No application code, `pom.xml` or other scaffolding exists yet; it will be added as a separate task.

## Related repositories

- `core-service`: application user profiles and core messaging logic
- `infrastructure`: local PostgreSQL and ZITADEL (Docker Compose)

## Branches

`TASK_<kebab-case>` -> `test` -> `main`, both through pull requests, enforced by the `branch-policy` workflow. Feature branches are created from `test`.
