# Programmatic API Onboarding — Salesforce

A single-file, zero-dependency Node.js (18+) CLI that reproduces SoundCloud's
`sc-api-auth.mjs` pattern for Salesforce: register an application / obtain credentials
programmatically instead of clicking through a dashboard, so agents and developers
can onboard at the command line.

- Script: [`salesforce-api-auth.mjs`](salesforce-api-auth.mjs)
- Run `node salesforce-api-auth.mjs --help` for usage and the required environment variables.
- Story / rationale: https://apievangelist.com/2026/09/02/salesforce-connected-apps-via-metadata/

Part of the API Evangelist "Programmatic API Onboarding for the Agentic Moment" series.
