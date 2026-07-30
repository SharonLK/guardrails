# Agent skills

- Skill permissions: 6 skills (`code-review`, `grill-me`, `implement`, `setup-matt-pocock-skills`, `to-spec`, `to-tickets`) are set to `ask` — get user approval before loading. All others (`grilling`, `tdd`) load automatically.
- Slash commands: `/code-review`, `/grill-me`, `/implement`, `/setup-matt-pocock-skills`, `/to-spec`, `/to-tickets` — these run in the main context (no subagent isolation).

## Domain docs

This is the opencode config repo itself. It holds guardrails, permissions, skills, and commands — not application code.
