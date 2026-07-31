# guardrails

Personal [opencode](https://opencode.ai) configuration and guardrails.

## What's here

- **`opencode.json`** — Main config: default agent (`plan`), permissions (read/edit/bash/skill), watcher ignores, LSP settings, formatter settings, snapshot/compaction options. 6 skills set to `ask` permission.
- **`.opencode/skills/`** — 8 workflow skills:
  - `code-review`, `grill-me`, `grilling`, `implement`, `setup-codebase`, `tdd`, `to-spec`, `to-tickets`
- **`.opencode/commands/`** — 6 slash commands wrapping skills for explicit invocation:
  - `/code-review`, `/grill-me`, `/implement`, `/setup-codebase`, `/to-spec`, `/to-tickets`
- **`.opencode/package.json`** — Plugin dependency (`@opencode-ai/plugin@1.18.9`).

## Usage

Sourced automatically when opencode runs in any directory that inherits these guardrails. Skills are agent-discoverable; the 6 with commands can also be invoked directly via `/name`.
