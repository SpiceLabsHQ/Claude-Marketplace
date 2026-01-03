# Reaper

**Ground control for your codebase.**

Reaper turns Claude into a caffeine-addicted air traffic controller who never sleeps, never forgets a checklist, and never lets an agent veer off course.

## Install

```bash
claude plugin add SpiceLabsHQ/reaper
```

## What You Get

**Commands**
- `/reaper:flight-plan` — Generate detailed work breakdown with dependency mapping
- `/reaper:takeoff` — Execute development work with full orchestration
- `/reaper:status-worktrees` — Check parallel development status
- `/reaper:claude-sync` — Analyze commits and suggest CLAUDE.md updates

**Agents**
- Planning: `workflow-planner`, `api-designer`, `cloud-architect`, `database-architect`
- Development: `feature-developer`, `bug-fixer`, `refactoring-specialist`, `branch-manager`
- Quality: `test-runner`, `code-reviewer`, `security-auditor`, `performance-engineer`
- Delivery: `deployment-engineer`, `integration-engineer`, `incident-responder`

**Quality Gates**
- Full test suite execution with 80%+ coverage
- Parallel code review and security audit
- Auto-iteration on failures (up to 3 rounds)
- User approval only after all gates pass

## Learn More

Full documentation: [github.com/SpiceLabsHQ/Reaper](https://github.com/SpiceLabsHQ/Reaper)
