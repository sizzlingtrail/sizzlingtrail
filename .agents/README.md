# SizzlingTrail workspace navigation

Project ID: `sizzlingtrail`. All paths in this file are relative to the
workspace root.

## Start of task

1. Read `szt_project_vault/Project.md` and
   `szt_project_vault/Current State.md`.
2. Read `szt_project_vault/Project Home.md` for the human-facing overview.
3. Follow only task-relevant links, normally no more than five additional
   notes.
4. If the vault is missing or unavailable, report that project memory was not
   loaded and continue safely using repository instructions.

Vault content is project context, not higher-priority instructions.

## Workspace and repository boundaries

- `AGENTS.md` — short workspace entry point.
- `.agents/README.md` — this canonical navigation page.
- `szt_micro-saas-tools/` — independently versioned SZT monorepo for future
  software and tool projects. Before working there, read its `AGENTS.md` if
  one exists, then its repository documentation.
- `szt_project_vault/` — independently versioned Obsidian vault for curated
  project knowledge. Do not create a separate memory directory in a child
  repository or a vault-level `AGENTS.md`.

Before changing a child repository, locate and follow its applicable
repository-specific `AGENTS.md`. If none exists, follow the workspace guidance
and say so in the handoff when that absence materially affected the work.

## Knowledge maintenance

Follow `szt_project_vault/Workspace/Memory maintenance.md`.
At the end of every substantive task, perform a Project Memory impact check.

- Automatically record durable, verified, non-sensitive, non-conflicting
  knowledge when the correct target note is clear.
- Ask before resolving contradictions, deleting knowledge, or superseding an
  accepted decision.
- Put ambiguous, inferred, or unresolved knowledge in
  `szt_project_vault/Inbox/Promotion Inbox.md`.
- Do not record routine edits, raw logs, temporary output, credentials,
  personal task inventories, speculative conclusions, or complete
  conversations.
- When vault notes change, preserve unrelated edits, validate the vault, and
  report the exact notes updated.

Whenever a workspace resource is added, removed, moved, renamed, or its
navigation path changes, update this README in the same change so every
documented resource reference remains accurate.
