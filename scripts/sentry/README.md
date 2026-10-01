# Sentry Triage Unresolved Issues Script

This script interacts with the Sentry API to fetch unresolved issues for a given project and organization.

## Environment Variables
- `SENTRY_AUTH_TOKEN`: Required for authentication.
- `SENTRY_ORG`: Organization name (default: `monoscope-ab`).
- `SENTRY_PROJECTS`: Project name (default: `monoscope-web`).

## Usage
Ensure the necessary environment variables are set and run the script with Node.js.
