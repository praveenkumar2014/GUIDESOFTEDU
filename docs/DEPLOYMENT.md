# Deployment Runbook

## Targets
Primary production: Ubuntu LTS + Docker + Coolify. Vercel may host a compatible frontend/preview when application and persistence needs fit.

## Preflight
Inspect repo, scripts, ports, server resources, existing containers/networks/volumes, firewall, DNS and backups. Do not change unrelated workloads.

## Release
Build/test immutable revision. Configure secrets in platform. Provision PostgreSQL and object storage with durable volumes/backups. Configure domain/TLS/health checks. Run reviewed migrations as controlled release. Verify public, auth, enquiry, enrolment and admin journeys.

## Recovery
Keep prior image/revision and tested DB restore procedure. Roll back app separately where schema compatibility allows; code rollback does not reverse data migrations.

## Vercel
Connect repository and configure correct root/build settings. Keep secrets in Vercel env vars. Verify build and deployment before announcing success.