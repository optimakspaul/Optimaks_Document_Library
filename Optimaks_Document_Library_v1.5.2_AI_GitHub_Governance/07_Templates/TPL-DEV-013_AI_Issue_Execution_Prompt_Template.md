# TPL-DEV-013 AI Issue Execution Prompt Template

| Field | Value |
|---|---|
| Template Code | TPL-DEV-013 |
| Version | v1.5.2 |
| Purpose | Standard prompt format for sending a GitHub Issue to Codex, Antigravity, or another AI development tool. |

---

## Prompt Template

```text
You are working on the repository: [repo name].

Current issue:
ISSUE-___: [Issue title]

Branch:
[feature/issue-xxx-short-name]

Read these documents first:
- [doc 1]
- [doc 2]
- [doc 3]

Constitution rules:
- Small Core First
- Workflow First
- One Core + Industry Template
- No scope expansion without Change Request
- Staging Test before Production Deploy
- No AI-generated code directly into main

Scope:
[Clearly list what this issue should do.]

Do not do:
[Clearly list excluded features and files / modules that should not be changed.]

Acceptance criteria:
[Paste acceptance criteria from GitHub Issue.]

Testing required:
[List commands and manual tests.]

After implementation, return:
- changed files
- commands run
- test result
- assumptions
- unresolved risks
- whether CHANGELOG / docs need update
```

---

## Tool Boundary Reminder

```text
Codex: backend, database, auth, RLS, CRUD, logic.
Antigravity: UI, layout, navigation, shared components, responsive, browser verification.
ChatGPT: scope, CR, issue refinement, prompt, QA, documentation.
```
