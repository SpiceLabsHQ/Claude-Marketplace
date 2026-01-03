# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the **Spice Labs Plugin Marketplace** - a curated registry for Claude Code plugins. It's a metadata-driven project (not a code library) that serves as the official distribution point for high-quality, opinionated plugins.

## Repository Structure

```
claude-marketplace/
├── .claude-plugin/
│   └── marketplace.json  # Marketplace manifest (required by Claude Code)
├── plugins/              # Plugin documentation (.md files)
└── README.md             # Project documentation
```

## Key Files

- **.claude-plugin/marketplace.json** - Marketplace manifest listing all plugins with source locations
- **plugins/*.md** - Detailed documentation for each plugin including commands, agents, and usage

## Working with This Repository

### Adding a New Plugin

1. Add plugin entry to `.claude-plugin/marketplace.json`:
```json
{
  "name": "plugin-name",
  "source": {
    "source": "github",
    "repo": "SpiceLabsHQ/plugin-name"
  },
  "description": "Brief description",
  "tags": ["relevant", "tags"]
}
```

2. Create `plugins/plugin-name.md` with full documentation

### Plugin Installation (for users)

```bash
claude plugin marketplace add SpiceLabsHQ/claude-marketplace
claude plugin install <plugin-name>@spice-labs
```

## Current Plugins

- **reaper** - Ground control for your codebase. Provides workflow orchestration with commands like `/reaper:flight-plan`, `/reaper:takeoff`, `/reaper:status-worktrees`, and `/reaper:claude-sync`.

## Standards

This marketplace follows Spice Labs standards:
- TDD-first development approach
- SOLID principles
- Quality over quantity - only well-documented, opinionated plugins are accepted
