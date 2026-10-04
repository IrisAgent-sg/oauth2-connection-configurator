# OAuth2 Connection Configurator

A static browser-only helper for building OAuth2 connection settings across common providers.

## Features

- Provider presets for GitHub, Google, Microsoft Entra, Slack, Notion, Discord, Spotify, Dropbox, GitLab, Linear, Atlassian, and Salesforce
- Authorization URL builder
- PKCE S256 code verifier/challenge generation
- Token exchange `curl` snippet
- Connection JSON export/import
- Provider-specific setup checklist
- No backend and no telemetry

## Security note

Do not enter or store client secrets in this site. Client secrets belong server-side, in a vault or secret manager. This tool is for public OAuth configuration values and local planning only.
