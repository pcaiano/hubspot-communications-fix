# HubSpot Communications Fix

Isolated executor for HubSpot communication preferences maintenance.

This repository is intentionally separate from ToolScout. It contains no HubSpot credentials. Runtime credentials are supplied only through Render environment variables.

Required Render environment variable:

- `HUBSPOT_PRIVATE_APP_TOKEN`

Runtime:

- Node.js
- Start command: `node hubspot-comm-fix.mjs`
- Health endpoint: `/health`
- Status endpoint: `/status`
