
# Keycloak Hands-On Training Repository

This repository provides a comprehensive, hands-on guide to mastering Keycloak and its key concepts, including:

- **Identity and Access Management (IAM)**: Core principles and best practices.
- **Authorization (Authz)**: Configuring permissions and resource access.
- **Authentication (Authn)**: Implementing secure user login and credential management.
- **Keycloak Installation**: Step-by-step setup for development and production environments.
- **Administration and Operation**: Managing realms, users, roles, and policies effectively.
- **Development**: Customizing Keycloak through extensions, themes, and integration with other systems.

## What You'll Find in This Repository:
- Practical exercises and examples for each concept.
- Detailed setup instructions for various environments.
- Sample configurations for real-world scenarios.
- Troubleshooting tips and best practices.

This repository is ideal for developers, administrators, and IT professionals looking to enhance their skills with Keycloak and modern IAM solutions.

## Installation

1. Copy .env.example file and rename to .env
2. Update variables of .env if is necessary
3. Startup docker and run this command:
```bash
docker compose up
```
4. Go to http://localhost:8080, use the credentials of .env file (default user: admin, pass: admin)