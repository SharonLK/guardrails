# Agent skills

- Skill permissions: 6 skills (`code-review`, `grill-me`, `implement`, `setup-codebase`, `to-spec`, `to-tickets`) are set to `ask` — get user approval before loading. All others (`grilling`, `tdd`) load automatically.
- Slash commands: `/code-review`, `/grill-me`, `/implement`, `/setup-codebase`, `/to-spec`, `/to-tickets` — these run in the main context (no subagent isolation).

### Issue tracker

Issues and specs live as markdown files in `.scratch/`. See `docs/agents/issue-tracker.md`.

### Domain docs

See `docs/agents/domain.md`.

## Domain docs

This is the opencode config repo itself. It holds guardrails, permissions, skills, and commands — not application code.
