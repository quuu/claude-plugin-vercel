# Vercel Deploy Plugin

Deploy to Vercel directly from Claude Code.

## Prerequisites

- [Vercel CLI](https://vercel.com/docs/cli) (`npm install -g vercel`)
- Vercel account (`vercel login`)

## Commands

| Command | Description |
|---------|-------------|
| `/deploy` | Deploy to production |
| `/vercel-logs` | View deployment logs |
| `/vercel-setup` | Set up Vercel CLI and project |

## Skills

Skills are auto-invoked based on context:

- **deploy** - "deploy my app", "push to production"
- **vercel-logs** - "show logs", "check deployment logs"
- **vercel-setup** - "set up Vercel", "configure Vercel"
