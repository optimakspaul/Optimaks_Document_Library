# FND-002 Development Constitution Overview

| Field | Value |
|---|---|
| Document Code | FND-002 |
| Version | v1.4.3 Integrated |
| Effective Date | 2026-05-14 |
| Owner | Optimaks Pte Ltd |
| Status | Active Integrated Constitution |
| Purpose | Provide the master overview of Optimaks development constitution from v1.3 to v1.4.3. |

---

## 1. Document Control

| Item | Value |
|---|---|
| Document Name | Optimaks Development Constitution / Optimaks 開發憲法 |
| Current Version | v1.4.3 Integrated |
| Effective Date | 2026-05-14 |
| Owner | Optimaks Pte Ltd |
| Applicable Scope | Optimaks OS, Aircon OS, ACRA Radar, internal tools, MVP/prototype systems, client workflow automation systems, AI-assisted development workflows |

---

## 2. Purpose

This constitution establishes a repeatable, traceable, reviewable, deliverable, and scalable AI-era development standard for Optimaks.

This is not merely a programming note. It is the operating standard for:

1. Idea capture and triage.
2. New features and bug fixes.
3. MVP decomposition and dependency control.
4. AI-assisted development execution.
5. UI / backend parallel development.
6. GitHub Issue and Change Request governance.
7. QA, staging, release, and documentation control.
8. Client delivery, monthly value, and maintenance governance.
9. Internal system development and future commercial delivery scaling.

---

## 3. Version Lineage

| Version | Role | Summary |
|---|---|---|
| v1.3 | Baseline governance | Established GitHub Markdown document library, mobile-assisted workflow, Codex + Antigravity architecture, CR flow, staging-before-production, QA, PDPA, ISO-ready and grant-ready structure. |
| v1.4 | Self-management and value control | Added idea triage, Mini Issue / Issue / CR / Full CR classification, daily priority rule, client value gate, AI execution control, and constitution upgrade trigger rule. |
| v1.4.1 | AI semi-automated pipeline patch | Added standard pipeline from idea to project brief, user flow, architecture, UI screen list, data model draft, issue breakdown, AI prompt, implementation, testing, GitHub diff, and changelog. |
| v1.4.2 | MVP decomposition patch | Added large-project decomposition, dependent vs independent MVP rule, MVP dependency map, and layered project documentation logic. |
| v1.4.3 | Small Core First and integrated operating patch | Integrates all previous versions and adds Small Core First Rule, document-as-AI-input rule, UI/backend parallel control, internal-vs-client delivery separation, layered MVP inheritance, monthly value rule, and version discipline. |

---

## 4. Highest Operating Principle

Any change should be traceable from:

```text
Idea
↓
Capture / Triage
↓
Issue / CR / MVP Document
↓
AI Execution Prompt
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

No idea should directly become code.

No large project should directly become a full product.

No AI tool should restart from zero when approved documents already exist.

---

## 5. Document Library Principle

The official source of truth should be Markdown files in GitHub.

```text
Markdown 分檔 = 正式原始文件
Word / PDF = 對外輸出或備份版本
GitHub diff = 版本比對證據
Issues / CR = 需求與變更證據
Staging = 安全驗證環境
Production = 審查後才可更新
```

Documents are not only records. Documents are development inputs.

Before AI-assisted implementation, the relevant constitution, MVP documents, project brief, data structure, page structure, constraints, acceptance criteria, and testing method must be provided as context.

---

## 6. Small Core First Principle

Optimaks projects must begin with a small, understandable, testable, and extendable core.

The first version of any internal or client system should avoid unnecessary complexity.

The first version should normally avoid, unless explicitly required:

1. Multi-tenant architecture.
2. Payment integration.
3. E-sign integration.
4. Full client portal.
5. Complex permission model.
6. Complete ERP scope.
7. Full reporting engine.
8. Production-grade automation across all modules.

The purpose is to make the first version stable, explainable, testable, and useful before expanding.

---

## 7. AI-Assisted Semi-Automated Development Principle

Optimaks uses AI to accelerate development, but AI must not replace governance.

```text
Paul decides direction.
AI accelerates execution.
GitHub records the truth.
Staging verifies safety.
Production changes only after review.
```

中文原則：

```text
Paul 負責方向與決策。
AI 負責加速整理、拆解、產出與實作。
GitHub 負責留下真相。
Staging 負責驗證安全。
Production 必須經過審查後才可更新。
```

---

## 8. MVP Layering Principle

Every meaningful MVP must have its own document package.

Dependent MVPs must inherit previous decisions, data assumptions, UI patterns, and accepted constraints.

Independent MVPs may prepare documents in parallel, but if they later integrate into Optimaks OS or a shared product platform, they must be reviewed as dependent modules.

```text
Large Idea
↓
MVP Decomposition
↓
Dependency Classification
↓
Step Documents
↓
AI Execution
↓
Review / Test / Merge
```

---

## 9. UI / Backend Parallel Development Principle

UI / UX and backend may run in parallel only when they share the same approved context.

The minimum shared context should include:

1. Project brief.
2. User flow.
3. Page map.
4. Component map.
5. Data model draft.
6. Field list.
7. Constraints and non-goals.
8. Acceptance criteria.

Antigravity may focus on UI, UX, layout, visual flow, and interaction. Codex may focus on code structure, data model, API logic, refactor, tests, and implementation quality.

Both outputs must be reconciled through GitHub diff and documentation update.

---

## 10. Internal Version vs Client Delivery Version Principle

Internal MVPs may be intentionally simple.

Client delivery versions must be more controlled.

| Area | Internal MVP | Client Delivery Version |
|---|---|---|
| Auth | May be omitted | Required when client or user data exists |
| Payment | Usually omitted | Required only if included in scope |
| E-sign | Usually omitted | Requires CR and client workflow review |
| Multi-tenant | Omitted | Requires Full CR / architecture review |
| Invoice | May be manual or omitted | Requires defined workflow and handover |
| QA | Basic testing | Formal QA checklist required |
| PDPA | Basic awareness | Formal PDPA/data protection review required |
| Handover | Not required | Required |
| Maintenance | Internal note | Monthly maintenance/value report required when monthly fee exists |

---

## 11. Monthly Value Principle

If Optimaks charges a monthly maintenance or system fee, the system or service should produce visible value evidence.

This may include:

1. System health check.
2. Uptime or deployment status.
3. Lead count.
4. Follow-up count.
5. Proposal status.
6. Issue / bug fix log.
7. Backup or maintenance record.
8. Content update record.
9. SEO / Google Maps / landing page performance indicators when applicable.
10. Monthly value summary for client communication.

This is a client delivery and maintenance governance rule. Specific implementation details should remain in the relevant project files.

---

## 12. Constitution Review Principle

The constitution should be reviewed only when a new rule affects repeated operations, AI execution, delivery governance, client promises, risk control, or company stage maturity.

```text
One-time idea → capture note / backlog / project file
Single feature → Issue or CR
Repeated operating rule → Constitution candidate
Company stage change → Major constitution upgrade
```

The constitution is not a notebook. It is the operating system of Optimaks.
