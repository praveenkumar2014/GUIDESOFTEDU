# API Conventions

Use /api/v1 for external APIs where practical. Validate request/response schemas. Return consistent success/error envelopes, appropriate HTTP statuses, pagination metadata and correlation IDs. Enforce auth, roles and tenant boundaries server-side. Rate-limit auth, lead and AI endpoints. Verify webhook signatures and process idempotently. Document contracts and permissions.