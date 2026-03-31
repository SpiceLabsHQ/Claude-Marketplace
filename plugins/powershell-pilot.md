# PowerShell Pilot

**PowerShell automation skills for Claude Code and Claude Desktop.**

PowerShell Pilot gives Claude a persistent, FIFO-backed PowerShell session manager — so commands, variables, loaded modules, and auth tokens all survive across multiple tool calls within a session.

## Install

```bash
claude plugin add SpiceLabsHQ/Claude-Powershell-Pilot
```

## What You Get

**Skills**
- `/pwsh` — Run PowerShell commands with full session and pipeline support

**Key Capabilities**
- **Persistent sessions** — Variables, modules, and auth tokens survive across tool calls; multiple named sessions run concurrently (e.g., `"readonly"` vs `"admin"`)
- **Session lifecycle** — Start, run, and stop named sessions via managed shell scripts
- **Device-code authentication** — Interactive auth flows for Azure, Microsoft Graph, Exchange Online, and SharePoint Online; device codes surface within seconds
- **Module management** — Install and load modules in-session with graceful missing-module detection
- **Output safety** — Stdout/stderr handled separately; output auto-truncated at 100 lines

**Works With**
- Azure
- Microsoft 365 / Exchange Online / SharePoint Online
- Microsoft Graph
- Any PowerShell module or automation workflow on macOS or Linux

## Learn More

Full documentation: [github.com/SpiceLabsHQ/Claude-Powershell-Pilot](https://github.com/SpiceLabsHQ/Claude-Powershell-Pilot)
