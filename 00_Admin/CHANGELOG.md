# Changelog

## v1.5.5 — Strategic Constitution Guardrails Patch — 2026-05-16

### Added

- Added formal v1.5.5 version definition: Strategic Constitution Guardrails, SWOT, Porter Five Forces and Lanchester Strategy Governance.
- Added `01_Foundation/FND-006_Strategic_Constitution_Guardrails.md`.
- Added `13_Strategy/STR-006_SWOT_ANALYSIS.md`.
- Added `13_Strategy/STR-007_PORTER_FIVE_FORCES.md`.
- Added `13_Strategy/STR-008_LANCHESTER_STRATEGY.md`.
- Added explicit strategic rules to prevent Optimaks from drifting into generic web agency, social media agency, heavy ERP / CRM provider, PSG reseller or unfocused custom software shop positioning.
- Added constitution-level scope rule: `Enquiry → Lead → Quote → Booking → Job Card → Invoice Status → Reminder`.
- Added feature classification rule: Core, Add-on, Future Version, Partner Service, Change Request or Rejected.
- Added Short Video Lead Kit guardrail: short video is a lead-source add-on, not full social media management.
- Added Lanchester first beachhead definition: Singapore aircon / field service SMEs with 3-10 workers or technicians.

### Updated

- Updated root `README.md` to v1.5.5.
- Updated `00_Admin/README.md`.
- Updated `00_Admin/VERSION_HISTORY.md`.
- Updated `01_Foundation/FND-002_Development_Constitution_Overview.md`.
- Updated `01_Foundation/FND-001_Company_Positioning.md` with v1.5.5 strategic guardrail note.
- Updated `13_Strategy/README.md` to include SWOT, Five Forces and Lanchester files.
- Updated `00_Admin/DOC-INDEX-001_Document_Index.md`.
- Updated `00_Admin/FILE_TREE.txt`.
- Updated `00_Admin/manifest.json`.

### Purpose

v1.5.5 converts the business strategy developed in v1.5.4 into practical constitution-level decision rules.

The goal is not to create more documents. The goal is to make sure every future product decision, client scope request, AI-generated implementation idea, pricing change and landing page message can be checked against Optimaks' approved strategy.

---

## v1.5.4 — AI Market Research & Strategy Governance Release — 2026-05-16

### Added

- Added formal v1.5.4 version definition: AI Market Research, Strategy Review, Pricing, GTM, Sales and Product Strategy Governance.
- Added `00_Admin/V1.5.4_SCOPE_DECISION.md` to clearly define why this release is v1.5.4 rather than v1.5.3.
- Consolidated the strategy review layer as an official release rather than an undefined v1.5.3 addendum.
- Clarified that `STD-DEV-025` remains the v1.5.3 research intake and multi-model handoff standard.
- Clarified that `STD-DEV-026` is the v1.5.4 business strategy governance standard.
- Added current-version metadata across active strategy, product strategy, sales, template, checklist, and governance files.

### Updated

- Updated root README to identify v1.5.4 as the active current release.
- Updated `FND-002_Development_Constitution_Overview.md` to make v1.5.4 the current active constitution version.
- Updated `VERSION_HISTORY.md`, `DOC-INDEX`, `FILE_TREE`, and `manifest.json`.
- Updated active section README files to reflect v1.5.4.
- Renamed the previous strategy-review scope decision into the official `V1.5.4_SCOPE_DECISION.md`.

### Governance Decision

- v1.5.3 is reserved for AI Research Intake and Multi-Model Handoff.
- v1.5.4 is reserved for AI Market Research, Strategy Review, Market Positioning, Pricing, GTM, Sales Playbook, and Product Strategy Governance.
- Market research output must not directly change product scope, pricing, website positioning, sales claims, or implementation tasks.
- Research output must become approved strategy documentation before it can become GitHub Issues or implementation prompts.
- The Source of Truth remains GitHub docs, GitHub Issues, PRs, changelog, and versioned strategy documents.

---

## v1.5.3 — AI Research, Strategy Review & Multi-Model Handoff Patch — 2026-05-16

### Added

- Added formal AI Research Intake and Multi-Model Handoff governance.
- Added formal AI Market Research and Strategy Review governance.
- Added `STD-DEV-025_AI_Research_Intake_and_Multi_Model_Handoff.md`.
- Added `STD-DEV-026_AI_Market_Research_and_Strategy_Review_Governance.md`.
- Added strategy documents under `13_Strategy/`:
  - `STR-001_MARKET_POSITIONING.md`
  - `STR-002_COMPETITOR_REVIEW_SG_SME.md`
  - `STR-003_PRICING_PACKAGES.md`
  - `STR-004_GTM_30_DAY_PLAN.md`
  - `STR-005_AI_MARKET_RESEARCH_STRATEGY_REVIEW_WORKFLOW.md`
- Added product strategy documents under `14_Product_Strategy/`:
  - `PRD-001_SERVICE_OS_PRODUCT_SCOPE.md`
  - `PRD-002_AIRCON_TEMPLATE_SCOPE.md`
- Added sales / GTM documents under `15_Sales_GTM/`:
  - `SAL-001_COLD_OUTREACH_PLAYBOOK.md`
  - `SAL-002_DISCOVERY_QUESTIONS.md`
  - `SAL-003_DEMO_SCRIPT.md`
- Added `TPL-BIZ-001_Strategy_Review_Template.md`.
- Added `CHK-BIZ-001_Market_Research_Strategy_Review_Checklist.md`.

### Updated

- Updated root README to position v1.5.3 as the active version.
- Updated VERSION_HISTORY, document index, file tree, and manifest.
- Added market research and strategy review boundary: Research Digest is not final strategy; final strategy must be reviewed and stored in official docs.

### Governance Decision

- Gemini / AI research digest may be used for large-context research, competitor analysis, API documentation, and market research.
- Gemini / AI research output must not directly become product scope, pricing, landing page claim, or implementation task.
- ChatGPT strategy review is required before research output becomes Optimaks strategy.
- Strategy decisions must be stored under `13_Strategy/`, `14_Product_Strategy/`, or `15_Sales_GTM/` before implementation.
- Implementation still requires GitHub Issue / Branch / PR / Preview / Human Review per v1.5.2 governance.

## v1.5.2 — AI Collaboration & GitHub Governance Patch — 2026-05-15

### Added

- Added formal AI collaboration governance for Codex, Antigravity, ChatGPT, GitHub Issues, feature branches, pull requests, and Vercel Preview.
- Added `STD-DEV-024_AI_Collaboration_GitHub_Execution_Governance.md`.
- Added `TPL-DEV-012_Pull_Request_Review_Template.md`.
- Added `TPL-DEV-013_AI_Issue_Execution_Prompt_Template.md`.
- Added `CHK-DEV-010_AI_GitHub_PR_Governance_Checklist.md`.
- Added `.github/pull_request_template.md`.
- Added `.github/ISSUE_TEMPLATE/ai_execution_task.md`.
- Added `00_Admin/V1.5.2_SCOPE_DECISION.md`.

### Updated

- Updated root README to v1.5.2.
- Updated `FND-002_Development_Constitution_Overview.md` with v1.5.2 active rules.
- Updated development standards README, templates README, and checklists README.
- Updated document index, file tree, manifest, and version history.

### Governance Decision

- AI-generated code must not directly enter `main`.
- Every meaningful implementation should follow one Issue / one Branch / one Pull Request.
- Codex and Antigravity must respect tool boundaries.
- Vercel Preview or staging test is required before production merge.
- Changelog / documentation evidence is required when functionality, architecture, security, or process changes.

## v1.5.1 — WAS Positioning Patch — 2026-05-14

### Added

- Added product positioning principle: Optimaks does not build generic SaaS; Optimaks builds industry-specific Workflow Automation Systems and SME Operating OS solutions.
- Added `FND-005_Product_Positioning_and_WAS_Principle.md`.
- Added `STD-DEV-023_Industry_Workflow_First_and_SME_OS_Scope_Standard.md`.
- Added `TPL-DEV-011_Industry_Workflow_Blueprint_Template.md`.
- Added `CHK-DEV-009_Workflow_Positioning_and_Scope_Checklist.md`.
- Added `00_Admin/V1.5.1_SCOPE_DECISION.md`.

### Updated

- Updated root README to v1.5.1.
- Updated company positioning to clarify WAS / SME OS direction.
- Updated constitution overview to include product positioning as an active rule.
- Updated document index, file tree, and manifest.

### Governance Decision

- Market research details such as Dynamics 365 pricing, JobStreet / SEEK job analysis, admin salary comparison, and sales scripts are not placed inside the constitution core. They should remain in project, sales, or market research documents unless they become repeated governance rules.

# CHANGELOG

## v1.5 Cleanup + Fusion — 2026-05-14

### Added

- Added `STD-DEV-020_AI_Context_Package_and_Semi_Automated_Execution_Standard.md`.
- Added `STD-DEV-021_MVP_Layering_Small_Core_and_Dependency_Execution_Standard.md`.
- Added `STD-DEV-022_Internal_MVP_Client_Delivery_and_Monthly_Value_Control_Standard.md`.
- Added `TPL-DEV-009_AI_Context_Package_Template.md`.
- Added `TPL-DEV-010_MVP_Layering_Template.md`.
- Added `CHK-DEV-008_v1.5_AI_and_MVP_Readiness_Checklist.md`.
- Added `00_Admin/CLEANUP_FUSION_REPORT_v1.5.md`.
- Added `12_Archive` for superseded historical documents.

### Changed

- Promoted v1.5 Cleanup + Fusion to v1.5 Cleanup + Fusion stable release.
- Rewrote root `README.md` for v1.5 positioning.
- Rewrote `FND-002_Development_Constitution_Overview.md` as active v1.5 constitution overview.
- Rebuilt document index, file tree, manifest, and version history.
- Simplified folder README files.
- Updated `CLT-006_Monthly_Maintenance_Report.md` to focus on client-facing report format and reference `STD-DEV-022` for governance principle.

### Archived

- Archived superseded v1.4.1 to v1.4.3 patch standards and templates under `12_Archive`.

---

# Changelog

| Field | Value |
|---|---|
| Document Code | ADM-001 |
| Current Version | v1.5 Cleanup + Fusion |
| Effective Date | 2026-05-14 |
| Owner | Optimaks Pte Ltd |
| Status | Active |
| Purpose | Track document library changes and explain what changed between versions. |

---

## v1.5 Cleanup + Fusion — 2026-05-14

### Added / Integrated

1. Integrated v1.4 governance rules for self-management, issue classification, AI execution control, and client value gate.
2. Integrated v1.4.1 semi-automated AI development pipeline.
3. Integrated v1.4.2 MVP decomposition, dependency mapping, and MVP document inheritance rules.
4. Added Small Core First and Layered MVP Execution Rule.
5. Added UI/backend parallel development and AI context control rule.
6. Added internal MVP vs client delivery version control rule.
7. Added monthly value visibility rule for recurring maintenance clients.
8. Corrected root README and folder README files to reflect v1.5 Cleanup + Fusion.
9. Regenerated document index to include files added after v1.3.
10. Added document review report for duplication, merge, deletion, and amendment recommendations.

### Important Note

v1.5 Cleanup + Fusion is a consolidation package built on the v1.3 clean document library baseline. Historical v1.3 files are kept for traceability, but v1.5 Cleanup + Fusion is the active operating version.

### Recommended Commit

```text
docs: update readme and index for Optimaks document library v1.4.3 integrated
```

---

## v1.3 — 2026-05-13

### Added

1. Mobile-Assisted Development Workflow.
2. Tool-role based mobile workflow instead of day/night schedule.
3. AI Tooling Workflow with Codex + Antigravity as formal development tools.
4. Antigravity model clarification: Claude and Gemini are internal model options, not standalone tools.
5. Mobile Capture Template: Idea / Reason / Done When.
6. Mobile Testing Checklist.
7. Staging / Preview / Production policy.
8. Documentation Update Workflow.
9. Project contexts for Optimaks OS, Aircon OS, and ACRA Radar.
10. Chapter-based Markdown document library structure.
11. Detailed version history file: `00_Admin/VERSION_HISTORY.md`.
12. GitHub cleanup guidance for recovering from messy uploads.

### Changed

1. Reorganized the full v1.3 constitution into a GitHub-ready document library.
2. Split the single full document into chapter-based Markdown files.
3. Strengthened Change Request, GitHub Issue, Branch, Commit, Push, Merge, QA, and deployment controls.
4. Clarified that phones are for capture, clarification, issue management, and preview testing.
5. Clarified that desktops are for implementation, integration, merge, and production release.
6. Corrected the AI tool hierarchy so Claude/Gemini are not documented as independent official tools.

### Preserved from v1.2

1. Change Request before code changes.
2. GitHub Issue as formal task source.
3. Staging / Preview before production replacement.
4. Document update and version tracking as mandatory controls.
5. Safer deployment principle: test first, then promote to production.

### Recommended Commit

```text
docs: consolidate Optimaks document library v1.3 with detailed version history
```

---

## v1.2 — 2026-05-13

### Added / Strengthened

1. Change Request workflow before code changes.
2. GitHub Issue as formal task source.
3. Branch-first development for safer changes.
4. Commit and push distinction.
5. Staging / Preview deployment before production replacement.
6. Documentation update requirement when functionality or process changes.
7. Impact analysis before sending tasks to Codex / AI tools.

### Important Principle

```text
Do not replace production directly.
First deploy to staging or preview.
Only promote to production after validation.
```

### Note

The uploaded v1.2 zip file did not contain readable files. This v1.2 entry is reconstructed from the active v1.3 changelog and prior constitution discussion.

---

## v1.0 — 2026-05-13

### Added

1. Initial Optimaks Development System Foundation.
2. Company-level development constitution.
3. Standard delivery process.
4. Change request process.
5. Project architecture template.
6. MVP spec template.
7. Integration contract template.
8. Data safety assessment template.
9. Pipeline spec template.
10. AI usage policy.
11. Release checklist template.
12. Initial ADRs.
13. Initial change request.

### Governance Principles Added

1. Architecture mode assessment: local-first, cloud-first, hybrid.
2. Data minimization.
3. Non-destructive processing.
4. Dry-run and review-before-apply.
5. MVP integration contract.
6. Shared core and modular extension.
7. Pipeline-first before UI.
8. AI-assisted, human-accountable development.
9. Review queue for low-confidence automation.
10. Continuous MVP integration.

---

## v0.1 — 2026-05-13

### Added

1. Initial Optimaks document library structure.
2. Standard development process.
3. Development constitution.
4. AI-assisted development workflow.
5. ISO-ready document structure.
6. Grant-ready preparation documents.
7. Client discovery, SOW, solution blueprint, QA, deployment, and handover templates.
8. Legal / commercial base documents.
9. Risk, change, lessons learned, and third-party service registers.

---

## Current Clean Baseline

The current baseline for GitHub should be:

```text
optimaks_document_library_v1_3
```

This folder should be treated as the latest clean source of truth for the document library.

---

## v1.4.3 - Integrated Constitution and Small Core First Patch

Date: 2026-05-14

### Added

1. Integrated v1.4, v1.4.1, and v1.4.2 packages into v1.3 full document library.
2. Added Small Core First and Layered MVP Execution Rule.
3. Added UI / Backend Parallel Development and AI Context Control Rule.
4. Added Internal MVP vs Client Delivery Version Control Rule.
5. Added version delta summary from v1.3 to v1.4.3.
6. Extended monthly maintenance report with monthly value evidence rule.

### Changed

1. Updated FND-002 to become v1.4.3 integrated master overview.
2. Clarified that documents are AI development inputs, not only records.
3. Clarified that internal MVPs may be simplified while client delivery versions require delivery controls.
4. Clarified that monthly fees should produce visible monthly value evidence.

### Governance Note

v1.4.3 does not activate v1.5. It is a patch-level integration and operating-rule clarification for v1.4.

---

## v1.5.3 — AI Research Intake & Multi-Model Handoff Patch

Date: 2026-05-16

### Added

- Added `STD-DEV-025_AI_Research_Intake_and_Multi_Model_Handoff.md`.
- Added `TPL-DEV-014_Gemini_Research_Digest_Template.md`.
- Added `CHK-DEV-011_AI_Research_Intake_and_Handoff_Checklist.md`.
- Added `V1.5.3_SCOPE_DECISION.md`.

### Updated

- Updated `STD-DEV-002` to recognize Gemini as an optional standalone Research Intake tool.
- Updated `STD-DEV-020` to add Research Intake Pre-Check before AI Context Package.
- Updated `STD-DEV-024` to require Gemini Digest → ChatGPT Review → AI Context Package before implementation.
- Updated `TPL-DEV-009` to reference Research Digest and ChatGPT review.
- Updated `TPL-DEV-013` to include Research / Handoff context controls.
- Updated `CHK-DEV-010` to include research handoff checks before PR merge.

### Governance Decision

Gemini may support large-context research and digest creation, but does not replace ChatGPT review, GitHub Issues, feature branches, PRs, VS Code diff review, or human approval.
