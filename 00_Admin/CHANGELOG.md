# Changelog

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
