---
name: AI Issue Release Safety
about: Use this for implementation issues that require merge, test, secret, rollback or deployment checks
title: "[AI-SAFE] ISSUE-XXX - "
labels: ["status:pending-review", "governance:v1.5.8"]
assignees: ""
---

# AI Issue Release Safety Template

## Issue ID

ISSUE-XXX

## Objective

Describe the exact objective.

## Assigned Tool

- [ ] Codex
- [ ] Antigravity
- [ ] ChatGPT review only
- [ ] Gemini research / review only
- [ ] Manual

## Required Governance Reading

- `README.md`
- `02_Development_Standard/STD-DEV-027_Repo_Workspace_and_AI_Execution_Boundary_Standard.md`
- `02_Development_Standard/STD-DEV-028_Interruption_Recovery_and_WIP_Preservation_Standard.md`
- `02_Development_Standard/STD-DEV-029_Rollback_and_Failed_Issue_Recovery_Standard.md`
- `02_Development_Standard/STD-DEV-030_Testing_Level_and_Validation_Standard.md`
- `02_Development_Standard/STD-DEV-031_Issue_Size_and_Splitting_Standard.md`
- `02_Development_Standard/STD-SEC-001_Environment_Secrets_and_API_Key_Governance.md`

## Issue Size Check

- [ ] Small enough to execute as one issue.
- [ ] Does not mix UI + DB + RLS + auth.
- [ ] Should be split before execution.

## Allowed Files to Modify

- `src/...`

## Do Not Modify

- `.env*`
- `supabase/migrations/` unless explicitly required
- RLS policies unless explicitly required
- Auth logic unless explicitly required
- Production deployment settings
- Unrelated routes/components

## Testing Level Required

- [ ] Level 0 — Docs
- [ ] Level 1 — Smoke
- [ ] Level 2 — UI Responsive
- [ ] Level 3 — Data Flow
- [ ] Level 4 — Security / RLS / Auth
- [ ] Level 5 — Release Gate

## Merge Readiness

- [ ] Scope checked
- [ ] Git diff reviewed
- [ ] Testing complete
- [ ] Secrets checked
- [ ] Rollback plan available if needed
- [ ] README / CHANGELOG updated if needed

## Recovery Plan

If this issue fails:

- [ ] Repair in same branch
- [ ] Revert files
- [ ] Revert commit
- [ ] Discard branch
- [ ] Split issue
- [ ] Founder review required
