# guardrails

Personal [opencode](https://opencode.ai) configuration and guardrails.

## What's here

- **`opencode.json`** — Main config: default agent (`plan`), permissions (read/edit/bash), watcher ignores, LSP settings, formatter settings, snapshot/compaction options.
- **`.opencode/skills/`** — Installed workflow skills:
  - `code-review`, `grill-me`, `grilling`, `implement`, `setup-matt-pocock-skills`, `tdd`, `to-spec`, `to-tickets`
- **`.opencode/package.json`** — Plugin dependency (`@opencode-ai/plugin@1.18.9`).

## Usage

Sourced automatically when opencode runs in any directory that inherits these guardrails.
