# GUIDESOFTEDU — Premium Product Build Prompt

Act as principal product designer, full-stack architect and implementation agent. Build a genuinely functional, production-oriented platform in this repository, not just a landing-page mockup.

## First: inspect
Read README.md, AI_AGENT_EXECUTION.md, TASKS.md and docs/*.md. Inspect repository, framework, package manager, existing implementation, Git state, scripts and deployment setup. Preserve unrelated work. Summarize findings and proceed with reversible code changes. Stop before destructive or billable external actions.

## Product
One platform and identity system for GUIDESOFT Academy, AI School, Career, Labs, Enterprise, Marketplace and Certification. Roles: visitor, learner, instructor, mentor, employer, enterprise manager, support and platform admin.

## Build the experiences
- Premium public site with specific value proposition, programme discovery, outcomes described responsibly, faculty/mentor profiles, practical learning, enterprise offer, FAQs, real enquiry forms and clear CTAs.
- Catalogue: search, filters, programme details, curriculum, prerequisites, delivery format, instructor, configurable transparent pricing and application path.
- Learner workspace: enrolments, progress, lessons, assignments, submissions, assessments, certificates and support.
- Instructor/mentor: assigned cohorts, lesson authoring, submissions review, feedback and progress.
- Career: profile, portfolio, readiness tasks, mock interviews and opportunities. No placement/salary guarantees.
- Enterprise: organizations, cohorts, seats, paths, reporting and invoicing workflow.
- Admin: leads, applications, programmes, users, cohorts, instructors, payments, support, content, audit trail and reports.
- Optional provider-agnostic AI learning assistant with consent, rate limits and clear limitations.

## Premium visual system
Original human-centered GUIDESOFT style, not competitor imitation. Sophisticated editorial layout, strong type scale, spacious grids, carefully art-directed real photography, meaningful data visualization, elegant learning cards, warm light surfaces balanced by ink-dark surfaces, restrained motion and polished responsive states. Use owner-provided brand assets if present; otherwise a typographic GUIDESOFT wordmark. No third-party logos/favicons, generic gradient blobs, robot imagery, fake data or invented testimonials. Add light/dark support where appropriate.

## Foundation
Preferred: Next.js App Router, TypeScript, Tailwind, accessible primitives, PostgreSQL, one ORM (Prisma or Drizzle), schema validation, secure auth, server APIs, tests, Docker and Coolify-compatible deployment. Pick compatible current versions. Modular monolith. Provider adapters for payments, email, video, storage and AI; integrations stay disabled until configured.

## Done means
Visible primary actions work. Forms validate and persist. Permissions enforced server-side. APIs return structured errors. Important actions audited. Migrations versioned. Uploads restricted. Webhooks signed and idempotent. Tests cover critical flows. Seed data is labelled demo-only. No fake success.

## Phases
A. Audit/scaffold/design tokens/lint/typecheck/test/build.
B. Public website/catalogue/lead capture/admin lead handling.
C. Auth/profiles/enrolment/learner dashboard.
D. LMS/cohorts/lessons/assignments/assessments/certificates.
E. Instructor, mentor, employer and enterprise workflows.
F. Payment, notifications, storage/video adapters and AI assistant.
G. Analytics, hardening, accessibility, performance, backups and deployment.

Deliver a working thin slice per phase. Update TASKS.md and docs. Do not claim production readiness until acceptance tests pass and services are configured. Primary production target: Ubuntu VPS with Coolify; Vercel may host compatible frontend/preview. Never commit secrets or perform destructive production actions.