# Optimaks Document Library v1.5.4 — AI Market Research & Strategy Governance

This repository is the official GitHub-ready governance and strategy document library for Optimaks Pte Ltd.

本文件庫是 Optimaks 的正式開發治理、AI 協作、市場研究、產品策略、定價與 GTM 文件庫。

**Current Active Version:** `v1.5.4 — AI Market Research & Strategy Governance Release`  
**Effective Date:** 2026-05-16  
**Owner:** Optimaks Pte Ltd  
**Status:** Active Current Release

---

## 1. Version Definition

```text
v1.5.2 = AI Collaboration + GitHub Execution Governance
v1.5.3 = AI Research Intake + Multi-Model Handoff Governance
v1.5.4 = AI Market Research + Strategy Review + Pricing / GTM / Sales Governance
```

### What this means

- **v1.5.2** controls how Codex / Antigravity / ChatGPT outputs enter GitHub through Issue, Branch, PR, Preview, human review, and changelog.
- **v1.5.3** controls how large-context research tools such as Gemini are used for API documents, PDFs, Open Data, long codebases, and multi-model handoff.
- **v1.5.4** controls how AI-generated market research becomes official Optimaks strategy, product positioning, pricing, GTM plans, sales scripts, and product strategy documents.

> v1.5.4 does not replace v1.5.2 or v1.5.3. It consolidates them and adds the business strategy governance layer.

---

## 2. Highest Operating Principle

```text
Research Digest is not strategy.
Strategy is not implementation.
Implementation is not production.
```

Optimaks must follow this chain:

```text
External Research / Market Data / API Docs
↓
Gemini or Research Digest
↓
ChatGPT Strategy / Architecture Review
↓
Approved Strategy / Product / Sales Docs
↓
GitHub Issue / AI Context Package
↓
Codex / Antigravity Implementation
↓
Branch / PR / Preview / Human Review
↓
Merge / CHANGELOG / Version Update
```

---

## 3. Active v1.5.4 Governance Standards

The current active governance layer includes:

1. `FND-001` — Company positioning.
2. `FND-002` — Development constitution overview.
3. `FND-005` — Product positioning and Workflow Automation System principle.
4. `STD-DEV-013` — Self-management, issue classification, AI execution, and client value control.
5. `STD-DEV-014` — Constitution upgrade trigger rule.
6. `STD-DEV-020` — AI Context Package and semi-automated execution standard.
7. `STD-DEV-021` — MVP layering, small core, and dependency execution standard.
8. `STD-DEV-022` — Internal MVP, client delivery, and monthly value control standard.
9. `STD-DEV-023` — Industry workflow-first and SME OS scope standard.
10. `STD-DEV-024` — AI collaboration and GitHub execution governance standard.
11. `STD-DEV-025` — AI research intake and multi-model handoff standard.
12. `STD-DEV-026` — AI market research and strategy review governance standard.

---

## 4. Top-Level Structure

```text
00_Admin                 Document index, changelog, version history, manifest, scope decisions
01_Foundation            Company positioning, constitution overview, product positioning principles
02_Development_Standard  Active development, AI, GitHub, MVP, research, and strategy governance standards
03_Client_Delivery       Client discovery, SOW, blueprint, milestone, handover, monthly report templates
04_Legal_Commercial      Quotation, payment, IP, PDPA, agreement checklist
05_ISO_Ready             ISO-ready control map, audit trail, risk and change control
06_Grant_Ready           Grant-ready evidence, case study and outcome report templates
07_Templates             CR, Issue, AI Context Package, Gemini Digest, Strategy Review templates
08_Checklists            QA, deployment, PDPA, AI PR, research handoff, market strategy checklists
09_Registers             Risk, change, lessons learned, and third-party registers
10_Projects              Optimaks OS, Aircon OS, and ACRA Radar project context files
11_Roadmap               Constitution roadmap
12_Archive               Historical / superseded documents only
13_Strategy              Market positioning, competitor review, pricing, GTM, strategy workflow
14_Product_Strategy      Optimaks Service OS and Aircon Template product scope
15_Sales_GTM             Cold outreach, discovery questions, demo script
```

---

## 5. Where Each Type of Content Belongs

| Content Type | Correct Location | Rule |
|---|---|---|
| AI execution rules | `02_Development_Standard/` | Must be followed before code generation |
| Market research digest | `13_Strategy/` or project research folder | Supporting evidence only, not final decision |
| Final positioning | `13_Strategy/STR-001_MARKET_POSITIONING.md` | Must be approved before landing page updates |
| Competitor analysis | `13_Strategy/STR-002_COMPETITOR_REVIEW_SG_SME.md` | Must be reviewed before sales claims |
| Pricing | `13_Strategy/STR-003_PRICING_PACKAGES.md` | Must be updated before public package changes |
| GTM plan | `13_Strategy/STR-004_GTM_30_DAY_PLAN.md` | Must guide outreach execution |
| Product scope | `14_Product_Strategy/` and `10_Projects/` | Must feed GitHub Issues and Codex prompts |
| Sales scripts | `15_Sales_GTM/` | Must match approved positioning |
| Implementation tasks | GitHub Issues + AI Context Package | Must not come directly from research digest |

---

## 6. Recommended Usage

```text
Markdown files = official source documents
GitHub Issues = task source
Branch / Commit / Pull Request = change evidence
Vercel Preview / staging = validation before production
Codex / Antigravity = execution agents under approved scope
ChatGPT = reasoning, strategy, architecture, QA, and governance reviewer
Gemini = optional large-context research / digest tool
12_Archive = history only, not current development instruction
```

---

## 7. Commit Message for This Release

```text
docs: release v1.5.4 AI market research and strategy governance
```
