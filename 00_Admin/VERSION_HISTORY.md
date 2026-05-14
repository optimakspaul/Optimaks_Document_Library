# Optimaks Development Constitution — Detailed Version History

| Field | Value |
|---|---|
| Document Code | ADM-003 |
| Current Library Version | v1.4.3 Integrated |
| Effective Date | 2026-05-14 |
| Owner | Optimaks Pte Ltd |
| Status | Active |
| Purpose | Record the evolution of the Optimaks development constitution and document library across uploaded versions. |

---

## Version Lineage Summary

```text
v0.1 Document Library
   ↓
v1.0 Development System Foundation
   ↓
v1.2 Development Constitution Update
   ↓
v1.3 Constitution Update Package
   ↓
v1.3 Markdown Document Library Structure
   ↓
v1.4 Governance and self-management upgrade
   ↓
v1.4.1 AI-assisted semi-automated development pipeline
   ↓
v1.4.2 MVP decomposition and dependency rule
   ↓
v1.4.3 Integrated Small Core First operating patch ← Current active version
```

---

## Source Packages Reviewed

| Source Package | Observed Status | Notes |
|---|---|---|
| `optimaks_document_library_v0_1` | Reviewed | Initial structured document library with folders for admin, foundation, development standard, client delivery, legal/commercial, ISO-ready, grant-ready, templates, checklists, and registers. |
| `optimaks-dev-system-foundation-v1.0` | Reviewed | Earlier foundation package with development constitution, delivery process, change request process, AI usage policy, ADRs, and release checklist templates. |
| `optimaks_document_library_v1_2` | Uploaded file contained no readable files | v1.2 changes are reconstructed from the current v1.3 changelog and our discussion notes: Change Request tightening, GitHub Issue usage, branch discipline, and staging-first deployment. |
| `Optimaks_Development_Constitution_v1.3_Package` | Reviewed | Single-file constitution package with v1.3 changelog, mobile capture template, GitHub issue template, Word/PDF/Markdown output. |
| `Optimaks_Document_Library_v1.3_Markdown_Structure` | Current base | Latest GitHub-ready document library with chapter-based Markdown files. |

---

# v0.1 — Initial Optimaks Document Library

## Purpose

v0.1 established the first company-style document library structure for Optimaks. It changed the work from scattered notes into a structured document system.

## Main Additions

- Established a multi-folder document library.
- Added admin document index and manifest.
- Added foundation documents for company positioning and development constitution.
- Added standard development workflow and AI-assisted development workflow.
- Added GitHub documentation SOP.
- Added client delivery templates: discovery form, scope of work, solution blueprint, milestone plan.
- Added legal/commercial draft files: quotation, agreement checklist, payment terms, IP/source code policy.
- Added ISO-ready and grant-ready folders.
- Added reusable templates, QA checklist, deployment checklist, handover checklist, PDPA checklist.
- Added initial registers: risk register, change register, lessons learned, third-party service register.

## Structural Impact

v0.1 introduced the idea that Optimaks documents should be maintained as a library rather than as one large document.

```text
00_Admin
01_Foundation
02_Development_Standard
03_Client_Delivery
04_Legal_Commercial
05_ISO_Ready
06_Grant_Ready
07_Templates
08_Checklists
09_Registers
```

## Importance

This version created the ISO-ready / grant-ready direction and made the document library suitable for GitHub version control.

---

# v1.0 — Development System Foundation

## Purpose

v1.0 focused on the development operating system itself. It defined the early rules for how Optimaks should plan, build, change, and release software with AI assistance.

## Main Additions

- Added company-level development constitution.
- Added standard delivery process.
- Added change request process.
- Added project architecture template.
- Added MVP specification template.
- Added integration contract template.
- Added data safety assessment template.
- Added pipeline specification template.
- Added AI usage policy.
- Added release checklist template.
- Added initial ADR records.
- Added initial change request record.

## Governance Principles Added

- Architecture mode assessment: local-first, cloud-first, hybrid.
- Data minimization.
- Non-destructive processing.
- Dry-run and review-before-apply.
- MVP integration contract.
- Shared core with modular extension.
- Pipeline-first before UI.
- AI-assisted, human-accountable development.
- Review queue for low-confidence automation.
- Continuous MVP integration.

## ADRs Introduced

| ADR | Topic |
|---|---|
| ADR-001 | Architecture Mode Assessment |
| ADR-002 | Non-destructive Processing |
| ADR-003 | MVP Integration Contract |
| ADR-004 | AI-assisted, Human-accountable Development |

## Difference from v0.1

v0.1 focused on document library structure. v1.0 focused on development governance and engineering principles.

---

# v1.2 — Safer Change, Branch, and Deployment Control

## Purpose

v1.2 strengthened the practical software-change workflow. The key idea was to prevent uncontrolled AI changes by forcing every meaningful change through Change Request, GitHub Issue, staging/preview testing, and documentation updates.

## Main Changes

- Strengthened Change Request before code changes.
- Added clearer GitHub Issue usage as the formal source of work.
- Added safer branch-based development logic.
- Reinforced commit and push distinction.
- Added staging / preview testing before replacing production.
- Added documentation update logic when features or workflows change.
- Added impact analysis before sending work to Codex or AI tools.

## Key Control Principle Added

```text
Do not replace production directly.
First deploy to staging or preview.
Only promote to production after validation.
```

## Practical Impact

v1.2 made the workflow safer for AI-assisted development by reducing the chance of:

- Direct changes to main branch.
- Production breakage from untested AI edits.
- Missing documentation updates.
- Losing track of why a change was made.
- Mixing multiple change requests into one uncontrolled update.

## Difference from v1.0

v1.0 defined the development foundation. v1.2 made the process stricter and more operational for real GitHub + Codex + deployment usage.

> Note: the uploaded `optimaks_document_library_v1_2` zip did not contain readable files, so this v1.2 record is reconstructed from the active v1.3 changelog and the established discussion history.

---

# v1.3 — Mobile-Assisted, AI Tooling Clarification, and Markdown Library Structure

## Purpose

v1.3 updates the constitution to reflect the real Optimaks operating model: mobile-assisted planning and testing, desktop-based implementation, GitHub Issue control, Codex implementation, and Antigravity as the AI IDE with selectable models.

## Major Additions

### 1. Mobile-Assisted Development Workflow

Added a formal workflow for using a phone as a development support tool.

```text
Mobile is not the main coding environment.
Mobile is the product manager control center.
```

Mobile is used for:

- Capturing ideas.
- Drafting lightweight CR notes.
- Creating or updating GitHub Issues.
- Testing Vercel Preview / staging links.
- Reporting bugs with screenshots.
- Supplementing acceptance results.

Desktop remains responsible for:

- Main implementation.
- Branch creation.
- Database schema and migration changes.
- Supabase RLS / auth / permission changes.
- Merge conflict handling.
- Final QA.
- Production deployment.

### 2. Changed Mobile Workflow from Time-Based to Tool-Based

The workflow was changed from a personal schedule model:

```text
Daytime = phone
Night = desktop
```

To a professional tool-role model:

```text
Mobile role
Desktop role
AI tool role
GitHub role
Staging role
Production role
```

Reason: a constitution should not depend on personal working hours. It should define tool responsibilities so it can scale when work schedules change or collaborators join.

### 3. Corrected AI Tooling Structure

Clarified the actual AI development stack.

Incorrect interpretation:

```text
Codex + Antigravity + Claude + Gemini
```

Correct v1.3 interpretation:

```text
Codex + Antigravity
              ├── Claude model option
              └── Gemini model option
```

Claude and Gemini are model options inside Antigravity, not separate official development tools in the Optimaks workflow.

### 4. Added AI Tooling Workflow

Core rule:

```text
ChatGPT = planning, CR, documentation
Codex = main implementation agent
Antigravity = AI IDE, UI iteration, review, testing support
Claude / Gemini = model options inside Antigravity
```

### 5. Strengthened GitHub Issue Workflow

Added clearer guidance for:

- Issue title format.
- Issue body minimum standard.
- Labels.
- Status flow.
- Mobile-to-GitHub capture.

### 6. Added Lightweight Mobile Capture Template

Added a simplified phone-friendly format:

```text
Idea:
What do I want to add or change?

Reason:
Why does this matter?

Done When:
How do I know it is completed?
```

This lightweight note must later be converted into a full Change Request before development.

### 7. Added / Updated Workflow Diagrams

v1.3 includes:

1. Standard Development Workflow.
2. Change Request Workflow.
3. AI Development Tooling Workflow.
4. Mobile-Assisted Development Workflow.
5. Staging / Preview / Production Deployment Workflow.
6. Documentation Update Workflow.

### 8. Reorganized into GitHub-Ready Markdown Library

The full constitution was split into chapter-based Markdown files:

```text
00_Admin
01_Foundation
02_Development_Standard
03_Client_Delivery
04_Legal_Commercial
05_ISO_Ready
06_Grant_Ready
07_Templates
08_Checklists
09_Registers
10_Projects
.github/ISSUE_TEMPLATE
```

## Difference from v1.2

v1.2 made the process safer. v1.3 makes the process more realistic, scalable, and easier to manage in GitHub.

---

# Current Recommended Version to Use

Use this package as the current clean version:

```text
optimaks_document_library_v1_3
```

Recommended Git branch:

```text
docs/clean-v1.3-document-library
```

Recommended commit message:

```text
docs: consolidate Optimaks document library v1.3 with detailed version history
```

---

# GitHub Desktop Recovery Note

If previous uploads made the repository messy, do not continue adding more random commits on top of the messy state. Recommended cleanup method:

1. Create a new branch from the current repository state.
2. Delete or archive duplicated/incorrect folders.
3. Copy this clean `optimaks_document_library_v1_3` folder into the repository.
4. Confirm the file tree matches `00_Admin/FILE_TREE.txt`.
5. Commit with the recommended commit message above.
6. Push the branch.
7. Review the diff before merging into main.

If the repo is very messy, a cleaner alternative is to create a fresh repo named:

```text
optimaks-document-library
```

Then upload this clean v1.3 package as the first stable baseline.

---

## v1.4.3 Integrated Constitution

| Field | Value |
|---|---|
| Version | v1.4.3 |
| Date | 2026-05-14 |
| Type | Integrated patch release |
| Based On | v1.3 full library + v1.4 + v1.4.1 + v1.4.2 |
| Main Theme | Small Core First, layered MVP execution, AI context control, internal/client delivery separation |

### Summary

v1.4.3 integrates all constitution versions from v1.3 through v1.4.2 and adds the missing operating rules discovered during MVP_01 and Aircon OS planning discussions.

### New Rules

1. STD-DEV-017 Small Core First and Layered MVP Execution Rule.
2. STD-DEV-018 UI Backend Parallel Development and AI Context Control Rule.
3. STD-DEV-019 Internal MVP vs Client Delivery Version Control Rule.

### Updated Files

1. FND-002 Development Constitution Overview.
2. CLT-006 Monthly Maintenance Report.
3. CHANGELOG.
4. VERSION_HISTORY.
5. VERSION_DELTA_SUMMARY v1.3 to v1.4.3.
