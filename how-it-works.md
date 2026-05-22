# How It Works

## High-level product structure

- Public marketing routes for home, about, action design, team, and contact.
- Bilingual route variants for the current live-site parity phase.
- Centralized public content, image assets, video references, shared header/footer, and contact form behavior.
- Validation covers lint, type checking, tests, Next build, and Cloudflare build output.

## Technology at a safe public level

- Next.js App Router, React, TypeScript, and vendored public assets/fonts.
- OpenNext on Cloudflare Workers for the target deployment path.
- A Cloudflare-compatible contact delivery path at a high level.
- GitHub Actions validation for the private repository.

## What is intentionally not documented here

- Source-code layout beyond broad product areas.
- API implementation details.
- Database schemas or migrations.
- Auth, session, token, or authorization internals.
- Deployment secrets, provider credentials, or private infrastructure.
- Hidden routes, internal prompts, proprietary algorithms, or client-sensitive data.
