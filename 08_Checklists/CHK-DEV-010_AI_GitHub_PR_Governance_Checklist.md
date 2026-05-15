# CHK-DEV-010 AI GitHub PR Governance Checklist

| Field | Value |
|---|---|
| Checklist Code | CHK-DEV-010 |
| Version | v1.5.2 |
| Purpose | Checklist for reviewing Codex / Antigravity / AI-generated code before merge. |

---

## 1. Issue and Branch Control

```text
[ ] The work is linked to one GitHub Issue.
[ ] The work is on a feature branch, not main.
[ ] Branch name follows issue naming convention.
[ ] The branch does not mix unrelated issues.
```

---

## 2. Tool Boundary

```text
[ ] Codex did not unexpectedly redesign UI.
[ ] Antigravity did not unexpectedly change database/auth/RLS logic.
[ ] If both tools modified the same area, the sequence is documented.
```

---

## 3. Scope Review

```text
[ ] The change matches the issue scope.
[ ] No future-version feature was added without CR.
[ ] No unrelated refactor was mixed into the PR.
[ ] Non-goals are respected.
```

---

## 4. Local Test

```text
[ ] npm install completed if dependencies changed.
[ ] npm run dev works.
[ ] npm run lint passes or issues are documented.
[ ] npm run build passes if applicable.
```

---

## 5. Security / Data Safety

```text
[ ] No real secrets committed.
[ ] No .env.local committed.
[ ] No service role key exposed to frontend.
[ ] client_id rule followed where applicable.
[ ] RLS not bypassed where applicable.
[ ] Cross-client data leakage risk considered.
```

---

## 6. Preview / Staging

```text
[ ] Vercel Preview generated.
[ ] Preview URL loads.
[ ] Main workflow tested in preview when applicable.
[ ] Production was not overwritten directly.
```

---

## 7. Documentation and Traceability

```text
[ ] PR links to issue.
[ ] PR describes included and excluded scope.
[ ] Test notes are recorded.
[ ] CHANGELOG updated if behavior/process changed.
[ ] Related docs updated if architecture/process changed.
```

---

## 8. Merge Decision

```text
[ ] Approved for merge.
[ ] Changes requested.
[ ] Blocked due to scope/security/test failure.
```
