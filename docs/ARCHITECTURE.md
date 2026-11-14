# Architecture

Start with a modular monolith: identity, catalogue, admissions, learning, cohorts, assessment, credentials, career, enterprise, commerce, communications, support and reporting.

Preferred stack: Next.js + TypeScript, Tailwind, accessible primitives, PostgreSQL, one ORM (Prisma or Drizzle), schema validation, Docker and Coolify. Separate Python worker only if measured AI/background workloads justify it.

Use server-side services and repository boundaries. Version API contracts and return structured errors. Start background jobs with a simple PostgreSQL-backed mechanism; add Redis only as needed. Use S3-compatible private object storage. Integrations use payment/email/video/AI adapters. Add structured logs, health checks and metrics.

Enforce tenant scoping in every data query and mutation. Use versioned migrations. Avoid premature microservices, Kubernetes, Kafka and vector databases.