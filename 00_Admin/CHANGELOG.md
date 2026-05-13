# Changelog

| Field | Value |
|---|---|
| Document Code | ADM-001 |
| Current Version | v1.3 |
| Effective Date | 2026-05-13 |
| Owner | Optimaks Pte Ltd |
| Status | Active |
| Purpose | Track document library changes and explain what changed between versions. |

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
