# OpenClaw

![Progress](https://progress-bar.dev/60)

An open-source AI coding assistant framework — a personal AI assistant you run on your own devices. Forked from [openclaw/openclaw](https://github.com/openclaw/openclaw).

## Tech Stack

- **TypeScript** — Core engine, CLI, plugin SDK
- **Python** — ML pipelines, sandbox tooling
- **Node.js** — Runtime, gateway, channel integrations

## Features

- Local-first Gateway — single control plane for sessions, channels, tools, and events
- Multi-channel inbox — WhatsApp, Telegram, Slack, Discord, Signal, iMessage, and 20+ more
- Multi-agent routing — route inbound channels/accounts/peers to isolated agents
- Voice Wake + Talk Mode — wake words on macOS/iOS, continuous voice on Android
- Live Canvas — agent-driven visual workspace with A2UI
- First-class tools — browser, canvas, nodes, cron, sessions
- Companion apps — macOS menu bar, iOS/Android nodes

## Roadmap

- [x] Core gateway architecture
- [x] Multi-channel messaging support
- [x] Plugin/extensions system
- [x] Voice interaction (macOS/iOS/Android)
- [x] Live Canvas & A2UI
- [ ] Enhanced sandboxing & security defaults
- [ ] Improved developer tooling & SDK docs
- [ ] Cross-platform desktop app polish
- [ ] Performance optimization & memory footprint reduction
- [ ] Community plugin marketplace

## Getting Started

```bash
npm install -g openclaw@latest
openclaw onboard --install-daemon
```

Runtime: **Node 22.14+**.

## Security

OpenClaw connects to real messaging surfaces. Treat inbound DMs as untrusted input. See [Security docs](https://docs.openclaw.ai/gateway/security) for DM pairing and sandboxing defaults.

## License

MIT — see [LICENSE](LICENSE). Original work by Peter Steinberger and the openclaw community.
