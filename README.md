# Optimaks Document Library v1.5.3  
## AI Research Intake & Multi-Model Handoff Patch

This repository is the official GitHub-ready document library for Optimaks development governance.

本文件庫是 Optimaks 的正式開發治理文件庫。  
目前有效版本為：

```text
v1.5.3 = AI Research Intake & Multi-Model Handoff Patch
```

v1.5.3 是建立在 v1.5.2 的 AI Collaboration & GitHub Governance 基礎上，不是推翻 v1.5.2，而是新增一層「大型資料導讀 / 多 AI 接力 / 實作前審查」流程。

---

## Current Active Version

```text
Current Active Version:
v1.5.3 AI Research Intake & Multi-Model Handoff Patch

Base Governance:
v1.5.2 AI Collaboration & GitHub Governance Patch
```

中文說明：

```text
v1.5.2 = 規範 Codex / Antigravity / GitHub Issue / Branch / PR / Preview / Human QA
v1.5.3 = 在 v1.5.2 上新增 Gemini Research Digest + ChatGPT Review + Multi-Model Handoff
```

---

## Version Positioning

```text
v1.3   = Clean GitHub-ready document library baseline
v1.4   = Governance upgrade: self-management, issue classification, AI execution control, client value gate
v1.4.1 = AI-assisted semi-automated development pipeline patch
v1.4.2 = MVP decomposition and dependency mapping patch
v1.4.3 = Small Core First and integrated operating patch
v1.5   = Cleanup + Fusion stable release
v1.5.1 = Product positioning patch: industry-specific WAS / SME Operating OS principle
v1.5.2 = AI collaboration patch: Codex / Antigravity + GitHub Issue / Branch / PR / Preview governance
v1.5.3 = AI research intake patch: Gemini / ChatGPT / Codex / Antigravity multi-model handoff governance
```

---

## What v1.5.3 Adds

v1.5.3 adds a formal pre-implementation research and review layer.

It is designed for situations involving:

```text
- Large documents
- API documentation
- Government open data
- Competitor research
- Client SOP documents
- Existing large codebases
- Complex third-party SaaS integration
```

The key principle is:

> Large external materials should not be sent directly to Codex or Antigravity for implementation. They must first be converted into a structured Research Digest, reviewed by ChatGPT, and then transformed into an AI Context Package, GitHub Issue, and implementation prompt.

中文核心治理：

> 大型文件、API 文件、Open Data、競品研究與客戶 SOP 不應直接丟給 Codex / Antigravity 實作。  
> 應先產生 Gemini Research Digest，再由 ChatGPT 做架構、策略、風險與 scope review，最後才轉成 AI Context Package、GitHub Issue 與 Codex / Antigravity prompt。

---

## Multi-AI Role Definition

```text
Gemini
= Large document / API / dataset / competitor research digest

ChatGPT
= Architecture, strategy, scope, risk, governance, prompt, and issue review

Codex
= Backend, Supabase, Auth, RLS, API, CRUD, tests, implementation

Antigravity
= UI, App Shell, navigation, responsive layout, browser verification

VS Code + GitHub
= Diff review, source control, PR, preview, approval, merge, and evidence trail
```

中文版本：

```text
Gemini = 讀大量資料
ChatGPT = 定規則與審查
Codex = 寫後端與邏輯
Antigravity = 做介面與預覽
VS Code + GitHub = 最終控制與留證據
```

---

## Required Workflow

The official v1.5.3 workflow is:

```text
Large Document / API / Dataset / Competitor Research
↓
Gemini Research Digest
↓
ChatGPT Architecture / Strategy / Risk Review
↓
AI Context Package
↓
GitHub Issue
↓
Feature Branch
↓
Codex / Antigravity Implementation
↓
VS Code Diff Review
↓
Preview / Local Test
↓
Pull Request
↓
Human Approval
↓
Merge
↓
CHANGELOG / VERSION_HISTORY / Docs Update
```

---

## Active v1.5.3 Governance Standards

The v1.5.3 active governance layer is centered on:

```text
FND-001      Company positioning
FND-002      Development constitution overview
FND-005      Product positioning and Workflow Automation System principle

STD-DEV-013  Self-management, issue classification, AI execution, and client value control
STD-DEV-014  Constitution review and upgrade trigger rule
STD-DEV-020  AI Context Package and semi-automated execution standard
STD-DEV-021  MVP layering, small core, and dependency execution standard
STD-DEV-022  Internal MVP, client delivery, and monthly value control standard
STD-DEV-023  Industry workflow-first and SME OS scope standard
STD-DEV-024  AI collaboration and GitHub execution governance standard
STD-DEV-025  AI Research Intake and Multi-Model Handoff standard
```

---

## New v1.5.3 Files

v1.5.3 adds the following files:

```text
00_Admin/
V1.5.3_SCOPE_DECISION.md

02_Development_Standard/
STD-DEV-025_AI_Research_Intake_and_Multi_Model_Handoff.md

07_Templates/
TPL-DEV-014_Gemini_Research_Digest_Template.md

08_Checklists/
CHK-DEV-011_AI_Research_Intake_and_Handoff_Checklist.md
```

---

## Updated Files in v1.5.3

v1.5.3 updates the following existing files:

```text
README.md

00_Admin/
CHANGELOG.md
DOC-INDEX-001_Document_Index.md
FILE_TREE.txt
VERSION_HISTORY.md
manifest.json

02_Development_Standard/
STD-DEV-002_AI_Assisted_Development_Workflow.md
STD-DEV-020_AI_Context_Package_and_Semi_Automated_Execution_Standard.md
STD-DEV-024_AI_Collaboration_GitHub_Execution_Governance.md

07_Templates/
TPL-DEV-009_AI_Context_Package_Template.md
TPL-DEV-013_AI_Issue_Execution_Prompt_Template.md

08_Checklists/
CHK-DEV-010_AI_GitHub_PR_Governance_Checklist.md
```

---

## Repository Structure

```text
00_Admin                 文件索引、版本紀錄、manifest、scope decision、file tree
01_Foundation            公司定位、開發憲法總覽、產品定位、WAS / SME OS 原則
02_Development_Standard  當前有效的開發流程、AI、GitHub、CR、MVP、交付治理標準
03_Client_Delivery       客戶交付、SOW、Blueprint、Handover、月費價值報告
04_Legal_Commercial      報價、付款、IP、PDPA、合約檢查
05_ISO_Ready             ISO-ready 控制對照與稽核證據
06_Grant_Ready           Grant-ready 證據包與案例模板
07_Templates             CR、Issue、AI Context Package、MVP、Workflow Blueprint、QA、Gemini Digest 等模板
08_Checklists            QA、部署、交接、PDPA、AI 執行、PR Governance、Research Intake checklist
09_Registers             CSV register：risk、change、lessons、third-party
10_Projects              專案 context：Optimaks OS、Aircon OS、ACRA Radar
11_Roadmap               憲法未來版本路線圖
12_Archive               歷史版本、舊 patch、已取代文件、重複資料夾封存
.github                  GitHub Issue / PR templates
```

---

## Important Governance Note

The current active version is:

```text
v1.5.3 AI Research Intake & Multi-Model Handoff Patch
```

Files under `12_Archive` are historical references only.  
They may explain how the rules evolved, but they should not override active files in:

```text
01_Foundation
02_Development_Standard
03_Client_Delivery
07_Templates
08_Checklists
```

---

## Recommended Usage

```text
Markdown 分檔 = 正式原始文件
Word / PDF = 對外輸出或備份版本
GitHub Issues = 任務來源
Branch / Commit / Pull Request = 變更軌跡
Gemini = 大型資料導讀與 Research Digest
ChatGPT = 架構、策略、風險與 scope review
Codex = 後端、資料庫、API、RLS、CRUD、測試實作
Antigravity = UI、App Shell、Navigation、Browser Preview
VS Code = Diff review 與本機控制
GitHub = Source of Truth、PR、merge、evidence trail
12_Archive = 歷史版本，不作為當前開發指令來源
```

---

## No Secret Rule

Do not send the following information directly into external AI tools:

```text
- .env files
- Supabase service role key
- API keys
- Client personal data
- Customer email / phone / address
- Contracts
- Invoices
- Payment records
- Confidential client SOPs without anonymization
```

Allowed research inputs should be:

```text
- Public API documentation
- Public open data
- Anonymized sample data
- Field structures
- Fake test data
- Non-sensitive workflow descriptions
- Public competitor website information
```

---

## Final Confirmation

```text
This repository keeps the existing Optimaks Document Library structure.

It does not create a separate v1.5.3 folder.

The repository content is now upgraded to:
v1.5.3 AI Research Intake & Multi-Model Handoff Patch.

The v1.5.2 governance rules remain active as the base layer.
The v1.5.3 research-intake and multi-model handoff rules are now added as the current active patch.
```
