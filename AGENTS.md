# Fanvue app starter — repository instructions

## Current scope
Next.js 16 App Router OAuth application starter with TypeScript, React, and pnpm. The repository is an app integration scaffold, not proof of a launched product. Begin with `README.md`, `package.json`, `src/app/api/oauth/`, `src/lib/`, and the environment schema.

## Security boundaries
- Keep OAuth client secrets, refresh/access tokens, cookies, and session data private and out of Git.
- Preserve redirect URL validation, CSRF/PKCE/session integrity, and least-privilege authorization.
- Never use production credentials or perform live API writes as routine tests.
- Distinguish demo integrations from supported, live account capabilities.
- Do not assume platform API terms or payment permissions without verifying current requirements.

## Development
Use the pnpm version stated by `package.json` and the README setup instructions. Documented commands include `pnpm dev`, `pnpm build`, and the package's `lint` script. Confirm local HTTPS and callback configurations before OAuth testing. Record actual validation results; do not claim successful platform activation from a local build.
