# Programmatic API Onboarding — Ping Identity

A single-file, zero-dependency Node.js (18+) CLI that reproduces SoundCloud's
`sc-api-auth.mjs` pattern for Ping Identity: register an application / obtain credentials
programmatically instead of clicking through a dashboard, so agents and developers
can onboard at the command line.

- Script: [`ping-identity-api-auth.mjs`](ping-identity-api-auth.mjs)
- Run `node ping-identity-api-auth.mjs --help` for usage and the required environment variables.
- Story / rationale: https://apievangelist.com/2026/08/01/ping-identity-two-roads-to-a-client/

Part of the API Evangelist "Programmatic API Onboarding for the Agentic Moment" series.
