# GUIDESOFTEDU — AI Agent Execution Guide

## Mission
Build GUIDESOFT Education & AI as a new, premium-quality platform. Do not clone Scaler code, branding, protected content or private workflows. Design GUIDESOFT independently using high-level public business patterns only.

## Compatible agents
Lovable, Bolt, GitHub Copilot, Cursor, Claude Code, OpenCode, Antigravity and any repository-aware coding agent.

## Required protocol
1. Read README.md, this guide, TASKS.md, LOVABLE_BUILD_PROMPT.md and all applicable docs/ files.
2. Inspect Git state, repository structure, package scripts, branches, existing code and deployment config. Preserve existing work.
3. Produce an audit of current state, missing capabilities, decisions, risks and plan.
4. Implement Phase 1 vertical slice before breadth: responsive public site, programme catalogue, lead capture, auth foundation and admin basics.
5. Implement real persistence, server-side role/tenant authorization, validation, audit events, tests and empty/loading/error/success states.
6. Continue in the sequence in docs/ROADMAP.md. Keep TASKS.md accurate.
7. Run only package scripts that exist. Run lint, typecheck, tests and production build; fix failures.
8. Document actual changed files, decisions, test results, incomplete work and deployment details.
9. Use small commits; never force-push or rewrite history.
10. Deploy only after checking target team/project, secrets, database, backups, migrations, domain and health checks.

## Premium visual quality
Create an original GUIDESOFT identity: editorial education brand, confident typography, generous whitespace, refined ink and warm-light surfaces, restrained accents, real-world human photography, purposeful diagrams, premium course cards and clear conversion hierarchy. Avoid generic AI gradients, excessive glass, template-looking dashboards, robot illustrations, fake testimonials and noisy animation. Responsive desktop/tablet/mobile. Support keyboard use, visible focus, semantic markup, strong contrast and reduced motion.

## Engineering constraints
- Prefer Next.js App Router + TypeScript + Tailwind + accessible components unless repository evidence justifies otherwise.
- PostgreSQL and one ORM, with versioned migrations.
- Server-verified authentication and authorization; enforce tenant/role boundaries on every protected operation.
- Validate uploads and default to private object storage.
- Payment adapters and server-verified, idempotent webhooks. Never trust client success.
- AI is optional, provider-agnostic, rate-limited and privacy-aware; basic product use must not require paid AI.
- Secrets only in platform env settings; .env.example contains names/placeholders only.
- No DB reset, production deletion, DNS replacement, force push or unapproved production migration.

## Final report
Report shipped features, files changed, commands and exit codes, test evidence, known gaps, required environment variable names (never values), deployment URL/status and rollback instructions. Never claim completion without evidence.