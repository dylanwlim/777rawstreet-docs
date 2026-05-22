# Build and Run

The source repository for 777 Raw Street remains private. The notes below are safe public-level orientation for people with source access.

## Local development

- Use Node.js 22+ and npm.
- Install dependencies with npm install.
- Run npm run dev for local parity review.
- Run npm run validate for lint, typecheck, tests, Next build, and Cloudflare build validation.
- Use private setup docs for Cloudflare authentication and contact delivery configuration.

## Validation

Use the private repository's documented validation scripts before publishing or deploying source changes. For documentation-only work, verify links, file names, and public-safe language before publishing.

## Public docs publishing

The private source repository contains a docs-only publish workflow. It copies allowlisted Markdown files from `docs-public/` into this public documentation repository and runs a leak check before publishing.
