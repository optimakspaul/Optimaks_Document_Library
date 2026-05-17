# Optimaks Document Library v1.5.8 — AI Repo Execution, Recovery and Release Safety Governance Patch

This repository is the official GitHub-ready governance, strategy, product, sales, partner, and AI-assisted development document library for Optimaks Pte Ltd.

本文件庫是 Optimaks 的正式開發治理、AI 協作、市場研究、產品策略、銷售 GTM、合作夥伴治理與公司戰略憲法文件庫。

**Current Active Version:** `v1.5.8 — AI Repo Execution, Recovery and Release Safety Governance Patch`  
**Effective Date:** 2026-05-17  
**Owner:** Optimaks Pte Ltd  
**Status:** Active Current Release

---

## 1. Version Definition

```text
v1.5.2 = AI Collaboration + GitHub Execution Governance
v1.5.3 = AI Research Intake + Multi-Model Handoff Governance
v1.5.4 = AI Market Research + Strategy Review + Pricing / GTM / Sales Governance
v1.5.5 = Strategic Constitution Guardrails + SWOT / Five Forces / Lanchester Governance
v1.5.6 = One-Person Team Operating Model + AI / Platform / Partner Role Boundaries
v1.5.7 = Short Video Lead Kit + Video Vendor / Partner Governance
v1.5.8 = AI Repo Execution + Recovery + Release Safety Governance
```

### What this means

- **v1.5.2** controls how Codex / Antigravity / ChatGPT outputs enter GitHub through Issue, Branch, PR, Preview, human review, and changelog.
- **v1.5.3** controls how large-context research tools such as Gemini are used for API documents, PDFs, Open Data, long codebases, and multi-model handoff.
- **v1.5.4** controls how AI-generated market research becomes official Optimaks strategy, product positioning, pricing, GTM plans, sales scripts, and product strategy documents.
- **v1.5.5** converts the approved strategy layer into constitution-level decision guardrails: company positioning, SWOT, Porter Five Forces, Lanchester strategy, scope boundaries, and AI / sales / product decision rules.
- **v1.5.6** adds the founder-led one-person team operating model and clarifies AI, platform, and external partner role boundaries.
- **v1.5.7** adds the Short Video Lead Kit add-on strategy and the governance controls for external video / UGC / white-label partners.
- **v1.5.8** adds the daily AI construction safety layer: repo/workspace execution, interruption recovery, rollback, merge readiness, testing, secrets, data, database and deployment gates.

> v1.5.8 does not replace v1.5.2 through v1.5.7. It adds the operational safety layer required for daily AI-assisted development using GitHub repo, local workspace, Codex, Antigravity, ChatGPT and Gemini.

---

## 2. Highest Operating Principle

```text
Research Digest is not strategy.
Strategy is not implementation.
Implementation is not production.
Positioning must govern scope.
Scope must govern AI execution.
AI tools and partners are not decision makers.
External partners are execution/support layers, not strategy owners.
GitHub repo is the central source of truth.
Local workspace is the active construction site.
Full repo context may be read, but only the assigned issue scope may be modified.
Interrupted AI work must be preserved through branch, commit, push and progress log.
Failed AI work must be recoverable through repair, revert, branch discard or controlled rollback.
Secrets must never enter prompts, frontend code, Git history, screenshots or public demos.
Founder review is required before acceptance, merge, deployment or client delivery.
```

Optimaks must follow this chain:

```text
External Research / Market Data / API Docs / Vendor Research
↓
Gemini or Research Digest
↓
ChatGPT Strategy / Architecture Review
↓
Approved Strategy / Product / Sales / Partner Docs
↓
Strategic Constitution Guardrails
↓
GitHub Issue / AI Context Package
↓
Repo / Workspace Pre-Implementation Scan
↓
Codex / Antigravity / External Partner Execution
↓
Branch / WIP Commit / PR / Preview / Human Review
↓
Merge Readiness / Release Safety Gate
↓
Merge / CHANGELOG / Version Update
```

---

## 3. v1.5.8 Strategic Addition

v1.5.8 formalizes the AI daily construction safety layer.

Approved execution model:

```text
GitHub Repo = Central Source of Truth
│
├─ ChatGPT
│   └─ GitHub App / Connector reads repo for strategy, documentation and review
│
├─ Codex
│   └─ Local workspace / Codex Web reads repo for code implementation
│
├─ Antigravity
│   └─ Local workspace reads repo for UI, prototype and page work
│
└─ Gemini
    └─ Gemini CLI / GitHub Action reads repo for research, triage, review and docs check
```

Core rule:

```text
Full repo is readable.
Only the assigned issue scope is editable.
```

ZIP files are allowed for archive, handover, backup, batch review or fallback only. They are not the default daily development source of truth.

v1.5.8 also adds the release safety layer:

```text
AI-generated work is not accepted simply because it runs.
It must pass issue scope, diff review, testing level, secrets safety, data safety, deployment gate and founder review.
```

---

## 4. Active v1.5.8 Documents

New in this release:

```text
00_Admin/V1.5.8_SCOPE_DECISION.md
02_Development_Standard/STD-DEV-027_Repo_Workspace_and_AI_Execution_Boundary_Standard.md
02_Development_Standard/STD-DEV-028_Interruption_Recovery_and_WIP_Preservation_Standard.md
02_Development_Standard/STD-DEV-029_Rollback_and_Failed_Issue_Recovery_Standard.md
02_Development_Standard/STD-DEV-030_Testing_Level_and_Validation_Standard.md
02_Development_Standard/STD-DEV-031_Issue_Size_and_Splitting_Standard.md
02_Development_Standard/STD-SEC-001_Environment_Secrets_and_API_Key_Governance.md
02_Development_Standard/STD-DATA-001_Mock_Demo_and_Client_Data_Governance.md
02_Development_Standard/STD-DEPLOY-001_Preview_Staging_Production_Gate_Standard.md
02_Development_Standard/STD-DB-001_Database_Migration_and_RLS_Change_Control.md
07_Templates/TPL-DEV-015_Issue_Starter_Pack_Governance_Insert.md
07_Templates/TPL-DEV-016_Issue_Progress_Log_Template.md
07_Templates/TPL-DEV-017_AI_Continuation_Prompt_Template.md
07_Templates/TPL-DEV-018_AGENTS_MD_Insert.md
07_Templates/TPL-DEV-019_GEMINI_MD_Insert.md
07_Templates/TPL-DEV-020_Failed_Issue_Recovery_Report_Template.md
07_Templates/TPL-DEV-021_Merge_Readiness_Report_Template.md
07_Templates/TPL-DEV-022_Testing_Result_Report_Template.md
08_Checklists/CHK-DEV-012_Repo_Workspace_Execution_Checklist.md
08_Checklists/CHK-DEV-013_Interruption_Recovery_Checklist.md
08_Checklists/CHK-DEV-014_Merge_Readiness_Checklist.md
08_Checklists/CHK-DEV-015_Rollback_Readiness_Checklist.md
08_Checklists/CHK-SEC-001_Secrets_and_ENV_Safety_Checklist.md
08_Checklists/CHK-QA-001_Testing_Level_Checklist.md
08_Checklists/CHK-DATA-001_Mock_Demo_Data_Checklist.md
08_Checklists/CHK-DEPLOY-001_Deployment_Gate_Checklist.md
08_Checklists/CHK-DB-001_Database_RLS_Change_Checklist.md
.github/ISSUE_TEMPLATE/ai_issue_execution_with_recovery.md
.github/ISSUE_TEMPLATE/ai_issue_release_safety.md
```

Core inherited governance remains active:

```text
FND-006 Strategic Constitution Guardrails
STD-DEV-024 AI Collaboration GitHub Execution Governance
STD-DEV-025 AI Research Intake and Multi-Model Handoff
STD-DEV-026 AI Market Research and Strategy Review Governance
STR-001 to STR-009 Strategy Layer
PRD-001 to PRD-003 Product Strategy Layer
SAL-001 to SAL-004 Sales GTM Layer
16_Partner_Governance Partner Layer
```

---

## 5. Top-Level Structure

```text
00_Admin                 Document index, changelog, version history, manifest, scope decisions
01_Foundation            Company positioning, constitution overview, product positioning, strategic guardrails
02_Development_Standard  Active development, AI, GitHub, MVP, research, strategy, role-boundary, repo/workspace, recovery and release safety standards
03_Client_Delivery       Client discovery, SOW, blueprint, milestone, handover, monthly report templates
04_Legal_Commercial      Quotation, payment, IP, PDPA, agreement checklist, vendor partnership terms
05_ISO_Ready             ISO-ready control map, audit trail, risk and change control
06_Grant_Ready           Grant-ready evidence, case study and outcome report templates
07_Templates             CR, Issue, AI Context Package, Gemini Digest, Strategy Review, Progress Log, Merge Readiness and Recovery templates
08_Checklists            QA, deployment, PDPA, AI PR, research handoff, market strategy, short video delivery, repo execution, recovery and release safety checklists
09_Registers             Risk, change, lessons learned, and third-party registers
10_Projects              Optimaks OS, Aircon OS, and ACRA Radar project context files
11_Roadmap               Constitution roadmap
12_Archive               Historical / superseded documents only
13_Strategy              Market positioning, competitor review, pricing, GTM, SWOT, Five Forces, Lanchester, short video strategy
14_Product_Strategy      Optimaks Service OS, Aircon Template, Short Video Lead Kit product scope
15_Sales_GTM             Cold outreach, discovery, demo, short video add-on sales scripts
16_Partner_Governance    External partner evaluation and outreach governance
```

---

## 6. Where Each Type of Content Belongs

| Content Type | Correct Location | Rule |
|---|---|---|
| Constitution-level positioning | `01_Foundation/` | Highest-level decision guardrails |
| One-person team operating model | `01_Foundation/FND-006` | Founder, AI, platform and partner role boundaries |
| AI role boundaries | `02_Development_Standard/STD-DEV-024` | AI tools execute; they do not decide scope |
| Repo/workspace execution boundary | `02_Development_Standard/STD-DEV-027` | Full repo readable; assigned issue scope editable |
| Interruption recovery | `02_Development_Standard/STD-DEV-028` | WIP must be preserved through branch, commit, push and progress log |
| Failed issue / rollback recovery | `02_Development_Standard/STD-DEV-029` | Failed AI work must be repairable, reversible or discardable |
| Testing level | `02_Development_Standard/STD-DEV-030` | Testing level must match risk level |
| Issue size and splitting | `02_Development_Standard/STD-DEV-031` | Large issues must be split before AI execution |
| Secrets governance | `02_Development_Standard/STD-SEC-001` | Secrets must never enter prompts, frontend code, Git history or demos |
| Mock / demo / client data governance | `02_Development_Standard/STD-DATA-001` | Demo data must be separated from real client data |
| Deployment gate | `02_Development_Standard/STD-DEPLOY-001` | Local, preview, staging and production require clear gates |
| Database and RLS change control | `02_Development_Standard/STD-DB-001` | DB/RLS changes require isolated, reviewable issues |
| Short video strategy | `13_Strategy/STR-009` | Must frame video as workflow-connected lead generation |
| Short video product scope | `14_Product_Strategy/PRD-003` | Defines Starter / Growth / Pro scope boundaries |
| Video vendor governance | `16_Partner_Governance/` | External vendors execute; they do not own clients or strategy |
| Vendor partnership terms | `04_Legal_Commercial/LEG-006` | Controls white-label, non-solicitation and revision terms |
| Implementation tasks | GitHub Issues + AI Context Package | Must not come directly from research digest |
| Issue recovery log | `issues/ISSUE-XXX/ISSUE-XXX_PROGRESS_LOG.md` | Required if work is interrupted |

---

## 7. Commit Message for This Release

```text
docs: release v1.5.8 AI repo execution recovery and release safety governance
```

Recommended commit description:

```text
Fuse the repo/workspace execution, interruption recovery, and release safety governance layers into the official v1.5.8 constitution release.

This update keeps v1.5.7 Short Video Lead Kit Partner Governance intact while adding repo-first AI execution, issue-scoped modification, WIP preservation, continuation prompts, rollback and failed issue recovery, merge readiness, testing level rules, secret safety, mock/demo data governance, database/RLS change control, and deployment gates.
```
