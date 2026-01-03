# Spice Labs Marketplace

**Claude Code plugins that actually work.**

We build opinionated tools for Claude Code. TDD-first, SOLID principles, quality gates that don't mess around. These plugins teach Claude how to coordinate complex workflows so you can focus on the work that matters.

> Built for us. Shared because why not.

## Quick Start

### 1. Add the Marketplace

```bash
claude plugin marketplace add SpiceLabsHQ/claude-marketplace
```

This registers the Spice Labs plugin registry with Claude Code.

### 2. Install a Plugin

```bash
claude plugin add SpiceLabsHQ/<plugin-name>
```

That's it. Claude handles the rest.

## Plugins

| Plugin | Description | Install |
|--------|-------------|---------|
| [Reaper](plugins/reaper.md) | Ground control for your codebase | `claude plugin add SpiceLabsHQ/reaper` |

## What Are Claude Code Plugins?

Plugins extend Claude Code with specialized agents, commands, and workflows. They're opinionated by design—we've done the thinking so Claude doesn't have to guess.

**What you get**:
- Specialized agents for planning, development, quality, and ops
- Slash commands that kick off coordinated workflows
- Quality gates that actually block bad code
- Zero-config installation

## License

MIT License. Copyright (c) 2026 Spice Labs.
