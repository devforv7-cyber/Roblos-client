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
The original cloudflare worker with all bindings and multiplayer/chat
```Link
https://roblos-client.antonyrozario2025.workers.dev/
```
