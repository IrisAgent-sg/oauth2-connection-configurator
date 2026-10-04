# OAuth2 Connection Configurator

A static, client-side helper for configuring OAuth2 app connections across common providers.

Live site: https://irisagent-sg.github.io/oauth2-connection-configurator/

## Features

- Provider presets for GitHub, Google, Microsoft, Slack, Discord, Notion, Linear, Reddit, X/Twitter, Spotify, Dropbox, Airtable, HubSpot, Zoom, and custom OAuth2.
- Generates authorization URLs.
- Generates PKCE code verifier and SHA-256 challenge locally in the browser.
- Generates token-exchange `curl` snippets.
- Generates environment variable templates.
- Generates provider JSON config.
- Includes an OAuth2 connection checklist.

## Security note

This is a static page. It does not store data and has no backend. Do not paste client secrets into the page. Client secrets belong server-side or in a secrets manager.
