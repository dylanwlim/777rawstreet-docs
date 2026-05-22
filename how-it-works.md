# How It Works

## Product structure

- Marketing routes cover home, about, action design, team, and contact.
- Bilingual route variants support the current live-site parity phase.
- Shared content, image assets, video references, header/footer, and contact form behavior keep the site consistent.
- Validation covers lint, type checking, tests, app build, and target hosting output.

## Technology

- Next.js App Router, React, TypeScript, and vendored public assets/fonts.
- OpenNext on Cloudflare Workers for the target deployment path.
- A Cloudflare-compatible contact delivery path at a high level.
- GitHub Actions validation for repeatable site checks.

## Update flow

- Product documentation changes are published to this guide repository automatically.
- A daily sync checks for guide updates after product work lands.
- Manual updates can also be published when a guide needs an immediate correction.
