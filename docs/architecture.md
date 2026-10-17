# DineDesk Architecture Overview

## Request Flow

1. The client sends an HTTP request to the web entry point.
2. Nginx acts as the reverse proxy.
3. The Next.js application handles the request and application logic.
4. The application accesses PostgreSQL for persistent data.
5. Health checks help verify application and database availability.

## Components

- **Web proxy:** Nginx
- **Application:** Next.js
- **Persistence:** PostgreSQL
- **Deployment:** Docker Compose

This document intentionally provides a high-level architectural overview and excludes internal source code, secrets, database records, and private deployment settings.
