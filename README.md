# ITSM Platform

The ITSM platform is a central hub for managing:
- Ticket management
- Service desk operations
- IT processes *(incidents, changes, CMDB, mapping)*
- Project management

It acts as an entrypoint and orchestrator for external applications, designed to:
- Centralize information
- Manage dependencies
- Ensure data consistency

It is a modular tool, consisting of a core module that can be extended with additional plugins as needed.

The frontend and backend are decoupled:
- The frontend is built using React.
- The backend is built using PHP/Symfony:
- It provides a RESTful API.
- It facilitates asynchronous communication between various microservices using RabbitMQ (Pub/Sub pattern).

## Tech Stack

- PHP 8
- Symfony 7
- React
- PostgreSQL 18
- RabbitMQ
- Docker
