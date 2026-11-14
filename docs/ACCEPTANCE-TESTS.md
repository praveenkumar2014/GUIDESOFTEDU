# Acceptance Tests

- Public pages render responsively and pass accessibility checks.
- Catalogue search/filter uses persisted programmes and useful empty/error states.
- Enquiry validates, persists and appears in admin with audit event.
- Unauthorized users cannot access restricted learner/instructor/employer/admin resources.
- Tenant users cannot access other organizations' records.
- Enrolments, progress and submissions persist across sessions.
- Instructors review only assigned cohorts/submissions.
- Payment state changes only after verified webhook; duplicate events safe.
- Certificate verification exposes only approved public data.
- AI endpoints enforce configured provider availability, consent and limits.
- Lint, typecheck, tests and production build pass.
- Backup/restore and deployment health checks are tested/documented before launch.