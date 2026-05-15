# FND-002 Development Constitution Overview

| Field | Value |
|---|---|
| Document Code | FND-002 |
| Version | v1.5.2 AI Collaboration & GitHub Governance Patch |
| Effective Date | 2026-05-15 |
| Owner | Optimaks Pte Ltd |
| Status | Active Stable Constitution with AI Collaboration & GitHub Governance Patch |
| Purpose | Provide the master overview of the Optimaks development constitution after v1.5 cleanup and fusion. |

---

## 1. Document Control

| Item | Value |
|---|---|
| Document Name | Optimaks Development Constitution / Optimaks 開發憲法 |
| Current Version | v1.5.2 AI Collaboration & GitHub Governance Patch |
| Effective Date | 2026-05-15 |
| Owner | Optimaks Pte Ltd |
| Applicable Scope | Optimaks OS, Aircon OS, ACRA Radar, internal tools, MVP/prototype systems, client workflow automation systems, AI-assisted development workflows |

---

## 2. Purpose

This constitution establishes a repeatable, traceable, reviewable, deliverable, and scalable AI-era development standard for Optimaks.

The constitution is not a notebook and not only a documentation archive. It is the operating system of Optimaks development.

It governs:

1. Idea capture and daily priority control.
2. Mini Issue / Issue / CR / Full CR classification.
3. MVP decomposition and dependency control.
4. Small Core First execution.
5. AI context package preparation.
6. Codex / Antigravity / ChatGPT division of responsibility.
7. GitHub Issue, branch, commit, diff, changelog, and documentation governance.
8. Internal MVP vs client delivery version control.
9. QA, staging, production, PDPA, handover, and maintenance evidence.
10. Monthly value visibility for subscription or maintenance clients.
11. Product positioning as industry-specific Workflow Automation Systems and SME Operating OS solutions.

---

## 3. Version Lineage

| Version | Role | Summary |
|---|---|---|
| v1.3 | Baseline governance | Established GitHub Markdown document library, mobile-assisted workflow, Codex + Antigravity architecture, CR flow, staging-before-production, QA, PDPA, ISO-ready and grant-ready structure. |
| v1.4 | Governance upgrade | Added self-management, daily priority, issue classification, AI execution control, client value gate, and constitution upgrade trigger rules. |
| v1.4.1 | AI pipeline patch | Added semi-automated AI development pipeline from idea to project brief, user flow, architecture, UI screen list, data model, issue breakdown, AI prompt, implementation, testing, GitHub diff, and changelog. |
| v1.4.2 | MVP decomposition patch | Added large-project decomposition, dependent vs independent MVP rule, MVP dependency map, and layered project documentation logic. |
| v1.4.3 | Integrated operating patch | Added Small Core First, document-as-AI-input rule, UI/backend parallel control, internal-vs-client delivery separation, monthly value rule, and version discipline. |
| v1.5 | Cleanup + Fusion stable release | Merged overlapping v1.4.1 to v1.4.3 patch files into fewer active standards and archived superseded files to reduce duplication and AI confusion. |
| v1.5.1 | WAS positioning patch | Added formal product positioning: Optimaks does not build generic SaaS; Optimaks builds industry-specific Workflow Automation Systems and SME Operating OS solutions. |
| v1.5.2 | AI collaboration governance patch | Added formal rules for Codex / Antigravity collaboration, one issue / one branch / one PR, AI code review, preview-before-production, batch scope boundary, and PR traceability. |

---

## 4. Highest Operating Principle

No idea should directly become code.

No large project should directly become a full system.

No AI tool should restart from zero when approved documents already exist.

Any meaningful change should be traceable from:

```text
Idea
↓
Capture / Triage
↓
Issue / CR / MVP Document
↓
AI Context Package
↓
Branch / Implementation
↓
Testing
↓
GitHub Diff Review
↓
Changelog / Documentation Update
↓
Staging
↓
Production Release
```

---

## 5. Active v1.5.2 Constitution Rules

### Rule 1 — Priority Before Execution

Every idea must pass through capture, triage, issue classification, and value check before it becomes implementation work.

Active reference: `STD-DEV-013`.

### Rule 2 — Constitution Is Updated Only When a Rule Becomes Repeated

The constitution should not be modified for every new thought. A rule should enter the constitution only when it affects repeated operation, AI execution, delivery governance, client promise, risk control, or company stage maturity.

Active reference: `STD-DEV-014`.

### Rule 3 — AI Requires a Context Package

AI should not be asked to build from a one-line prompt when the task affects system structure. Before AI execution, provide the constitution, project context, scope, non-goals, data model, page map, acceptance criteria, and test method.

Active reference: `STD-DEV-020`.

### Rule 4 — Small Core First

Every software product or workflow automation project should start from the smallest useful core that is understandable, testable, and extendable.

Active reference: `STD-DEV-021`.

### Rule 5 — MVPs Must Be Layered by Dependency

Dependent MVPs inherit previous decisions, data assumptions, UI patterns, constraints, and testing outcomes. Independent MVPs may be prepared in parallel, but must be reviewed again before integration.

Active reference: `STD-DEV-021`.

### Rule 6 — UI and Backend Can Run in Parallel Only with Shared Context

Antigravity may focus on UI/UX and visual flow. Codex may focus on implementation, refactor, data structure, APIs, and tests. Both must share the same approved context package and be reconciled through diff review.

Active reference: `STD-DEV-020`.

### Rule 7 — Internal MVP and Client Delivery Are Not the Same Standard

Internal MVPs may omit auth, payment, e-sign, invoice, client portal, multi-tenant architecture, and full reporting if the purpose is validation. Client delivery versions require stronger QA, PDPA, deployment, handover, support boundary, and maintenance governance.

Active reference: `STD-DEV-022`.

### Rule 8 — Monthly Fees Require Visible Monthly Value

If Optimaks charges a recurring system, hosting, maintenance, or support fee, there should be visible monthly value evidence, such as system health, bug fixes, backup, uptime, lead/follow-up activity, content updates, or performance indicators.

Active reference: `STD-DEV-022` and `CLT-006`.

---

### Rule 11 — Product Positioning Before Product Expansion

Optimaks does not build generic SaaS products. Optimaks builds industry-specific Workflow Automation Systems and SME Operating OS solutions around real workflows.

Before a project becomes an implementation task, it must define the target industry, real workflow, pain point, Small Core MVP, data flow, and value proof.

Active references: `FND-005` and `STD-DEV-023`.

## 6. Source of Truth Rule

```text
Markdown 分檔 = 正式原始文件
GitHub Issues = 任務來源
GitHub branch / commit / PR = 變更軌跡
GitHub diff = review evidence
Staging = safety verification
Production = approved release only
12_Archive = historical reference only
```

Word, PDF, or chat outputs may be useful for presentation or backup, but the GitHub Markdown library is the operational source of truth.

---

## 7. Archive Rule

Files under `12_Archive` are preserved for traceability.

They should not override active v1.5 files.

When giving context to ChatGPT, Codex, Antigravity, or another AI tool, use active v1.5 files first. Use archive files only when reviewing how a rule evolved.

---

## 8. Current Active Standards

| Standard | Current Role |
|---|---|
| `STD-DEV-013` | Priority, issue classification, AI execution, and client value control |
| `STD-DEV-014` | Constitution upgrade trigger and version governance |
| `STD-DEV-020` | AI context package, semi-automated execution pipeline, and UI/backend reconciliation |
| `STD-DEV-021` | MVP decomposition, dependency control, Small Core First, and layered execution |
| `STD-DEV-022` | Internal MVP vs client delivery standard and monthly value control |

---

## 9. Next Recommended Version Direction

v1.5 should be treated as the stable operating release for near-term Optimaks development.

Future versions should not be created only because of new ideas. A new version should be considered only when the operating model changes again, such as:

1. Optimaks starts repeated paid client delivery.
2. Multi-tenant SaaS becomes an active architecture requirement.
3. A formal legal / PDPA / contract pack becomes mandatory.
4. A standardized client onboarding and support workflow becomes repeatable.
5. AI development tools or deployment architecture materially change.

---

## v1.5.2 Patch Addendum — AI Collaboration & GitHub Execution Governance

The following rules are added as active constitution rules from v1.5.2 onward.

### Rule 12 — One Issue / One Branch / One PR

Every implementation task should be traceable through one GitHub Issue, one feature branch, and one Pull Request.

Direct development on `main` is not allowed for meaningful implementation work.

Active reference: `STD-DEV-024`.

### Rule 13 — AI Code Requires Human Review

Code generated by Codex, Antigravity, or any other AI development tool must be reviewed through git diff, local test, PR review, and preview / staging test before merge.

Active reference: `STD-DEV-024` and `CHK-DEV-010`.

### Rule 14 — Codex and Antigravity Must Respect Tool Boundaries

Codex is primarily responsible for backend, Supabase, Auth, RLS, CRUD, workflow logic, reporting, and refactoring.

Antigravity is primarily responsible for UI layout, App Shell, navigation, shared components, responsive design, and browser-based UI verification.

Active reference: `STD-DEV-024`.

### Rule 15 — Batch Scope Boundary

Each development batch must do only its approved scope.

If an AI tool adds future-version features or unrelated implementation, the extra work must be removed, rejected, or converted into a Change Request.

Active reference: `STD-DEV-024`.

### Rule 16 — Client Workspace Data Isolation Is a Core Safety Rule

All client-owned operational records must include `client_id` and use the `profiles / clients / client_users` relationship to support workspace-based access.

RLS policies must be used to prevent cross-client data leakage before client demo or delivery.

Active reference: `STD-DEV-024`.

### Rule 17 — Preview Before Production

Feature branches must be tested through local test and Vercel Preview or staging before production merge.

Production is an approved release target, not an experiment area.

Active reference: `STD-DEV-024` and `STD-DEV-007`.

### Rule 18 — Issue / Changelog Traceability

Completed work must leave traceable evidence through GitHub Issue status, PR notes, test results, changelog updates, and documentation updates where applicable.

Active reference: `STD-DEV-024` and `STD-DEV-008`.
