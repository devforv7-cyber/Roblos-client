# ROBLOS Classic Client

A browser-based classic 3D place playtest client. This public-source edition is a standalone static HTML build with multiplayer and room chat removed.

## Features
- Built-in Crossroads and LuauBlock test places
- Open local `.rbxlx` / XML place files
- Desktop keyboard and mobile touch controls
- Avatar appearance customization
- No multiplayer, room chat, WebSocket connection, or server binding required
- No API keys are included in this source bundle

## Run locally
Open `index.html` in a modern browser (Chrome or Edge recommended). If local-file restrictions prevent it from running, use Python's static server:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Publish
Upload the files to a GitHub repository. You can enable GitHub Pages from the repository settings; no Worker bindings or secrets are required.

## Scope
This is the standalone classic-client HTML source recovered from project files available for this export. It is not a complete export of the current `roblos-client` Cloudflare Worker, embedded Studio/IDE routes, or Durable Object implementation.
