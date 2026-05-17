---
name: AI Issue Execution With Recovery
about: Use this template for Codex / Antigravity implementation issues
title: "[AI] ISSUE-XXX - "
labels: ["status:pending-review"]
assignees: ""
---

# AI Implementation Issue

## Issue ID

ISSUE-XXX

## Objective

Describe what should be implemented.

## Assigned Tool

- [ ] Codex
- [ ] Antigravity
- [ ] ChatGPT review only
- [ ] Gemini research / review only
- [ ] Manual

## Required Reading

- `AGENTS.md`
- `README.md`
- `01_Foundation/FND-002_Development_Constitution_Overview.md`
- `02_Development_Standard/STD-DEV-024_AI_Collaboration_GitHub_Execution_Governance.md`
- `02_Development_Standard/STD-DEV-027_Repo_Workspace_and_AI_Execution_Boundary_Standard.md`
- `02_Development_Standard/STD-DEV-028_Interruption_Recovery_and_WIP_Preservation_Standard.md`
- `issues/ISSUE-XXX/ISSUE-XXX_STARTER_PACK.md`

## Dependency Map

Depends on:

- ISSUE-___
- ISSUE-___

Existing files to inspect:

- `src/...`
- `docs/...`

## Allowed Files to Modify

- `src/...`
- `docs/...`

## Do Not Modify

- `docs/constitution/`
- `supabase/migrations/`
- RLS policies
- Auth logic
- Tenant isolation logic
- Production deployment settings
- Unrelated routes/components

## Branch

Recommended branch:

```text
feature/issue-XXX-short-description
```

## Interruption Recovery

If interrupted, update:

```text
issues/ISSUE-XXX/ISSUE-XXX_PROGRESS_LOG.md
```

Recovery rule:

- Do not restart from scratch.
- Inspect latest commit, git status, issue starter pack, and progress log.
- Continue only remaining work.

## Acceptance Criteria

- [ ] Meets issue objective
- [ ] Does not break existing routes
- [ ] Uses existing shared components where possible
- [ ] Does not bypass RLS / auth / tenant isolation assumptions
- [ ] Mobile responsive if UI is changed
- [ ] Works locally
- [ ] Works on Vercel Preview if UI/routing changed
- [ ] No hardcoded client data
- [ ] README / CHANGELOG updated if needed
- [ ] Progress log updated if interrupted
