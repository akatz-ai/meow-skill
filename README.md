# MEOW Skill for Claude Code

A Claude Code skill for [MEOW](https://github.com/akatz-ai/meow) (Meow Executors Orchestrate Work) - the Makefile of AI agent orchestration.

## Installation

### Add the marketplace

```bash
/plugin marketplace add akatz-ai/meow-skill
```

### Install the plugin

```bash
/plugin install meow
```

## What's Included

The MEOW skill helps you:

- **Create workflows** - Write TOML templates that orchestrate AI agents
- **Run workflows** - `meow run`, `meow status`, `meow stop`
- **Monitor agents** - Check status, attach to tmux sessions, view logs
- **Debug issues** - Troubleshoot stale workflows, agent hangs, lock conflicts

## Skill Contents

| File | Purpose |
|------|---------|
| `SKILL.md` | Core documentation - quick start, executors, monitoring |
| `references/commands.md` | Complete CLI reference |
| `references/templates.md` | Template syntax guide (7 executors) |
| `references/patterns.md` | Common workflow patterns |
| `references/troubleshooting.md` | Debugging guide |

## Prerequisites

This skill helps you use MEOW, so you'll need the `meow` CLI installed:

```bash
# Quick install (Linux/macOS)
curl -fsSL https://raw.githubusercontent.com/akatz-ai/meow/main/install.sh | sh

# With Go
go install github.com/akatz-ai/meow/cmd/meow@latest

# Or from source
git clone https://github.com/akatz-ai/meow
cd meow && make install
```

## Usage

Once installed, the skill automatically activates when:

- You're working in a project with a `.meow/` directory
- You ask about MEOW workflows, templates, or orchestration
- You use `meow` CLI commands
- You need to debug agent workflows

## Links

- [MEOW Repository](https://github.com/akatz-ai/meow)
- [MEOW Documentation](https://github.com/akatz-ai/meow/blob/main/docs/ARCHITECTURE.md)

## License

MIT
