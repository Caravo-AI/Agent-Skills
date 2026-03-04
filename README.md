# Caravo Agent Skills

Agent Skills for [Caravo](https://caravo.ai) — non-MCP agent integration for OpenClaw, Claude Code, Cursor, Codex, and 40+ other agents.

## Install

### ClawHub (OpenClaw)

```bash
npx clawhub@latest install caravo
```

Or send a message to OpenClaw:

```
Read and install https://caravo.ai/skill.md
```

### Vercel Skills CLI

```bash
npx skills add Caravo-AI/Agent-Skills
```

### Manual (curl)

Download the skill file directly. The content at `caravo.ai/skill.md` is identical to this repo's `SKILL.md` — it's a proxy that always serves the latest version from GitHub.

```bash
curl -fsSL https://caravo.ai/skill.md \
  --create-dirs -o ~/.openclaw/skills/caravo/SKILL.md
```

## What's Inside

`SKILL.md` — A comprehensive agent skill that teaches AI agents how to use Caravo's marketplace via the `caravo` CLI. Supports both API key authentication and x402 USDC payments.

The skill covers:
- Tool search and discovery
- Tool execution with automatic payment
- Review and upvote system
- Tool request submission

## Requirements

- Node.js (for `npx` to auto-install the CLI)
- Either `CARAVO_API_KEY` env var or USDC on Base for x402 payments

## Ecosystem

- [caravo.ai](https://caravo.ai) — Official website and marketplace
- [Caravo-MCP](https://github.com/Caravo-AI/Caravo-MCP) — Official MCP server (`@caravo/mcp`)
- [Caravo-CLI](https://github.com/Caravo-AI/Caravo-CLI) — Command-line interface (`@caravo/cli`)

## License

MIT
