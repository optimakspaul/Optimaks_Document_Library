# Optimaks Document Library v1.5.2 AI Collaboration & GitHub Governance Patch

This repository is the official GitHub-ready document library for Optimaks development governance.

本文件庫是 Optimaks 的正式開發治理文件庫。v1.5.2 是在 v1.5.1 WAS Positioning Patch 的基礎上，新增「AI 協作開發 / GitHub branch / PR / Preview / Human QA」憲法級治理規範。

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
```

## What v1.5.2 Adds

v1.5.2 does not replace v1.5.1. It keeps the WAS / SME OS positioning and adds execution governance for AI-assisted coding.

The key principle is:

> AI-generated code should not directly enter main. Every meaningful implementation must go through GitHub Issue, feature branch, Pull Request, preview / staging test, human review, and traceable documentation.

中文核心治理：

> Codex / Antigravity 產出的程式碼不得直接進 main。每個實作任務必須經過 Issue、Branch、PR、Preview、人工驗收與 Changelog / 文件追蹤。

## Active v1.5.2 Governance Standards

The v1.5.2 active governance layer is centered on:

1. `FND-001` — Company positioning.
2. `FND-002` — Development constitution overview.
3. `FND-005` — Product positioning and Workflow Automation System principle.
4. `STD-DEV-013` — Self-management, issue classification, AI execution, and client value control.
5. `STD-DEV-014` — Constitution review and upgrade trigger rule.
6. `STD-DEV-020` — AI Context Package and semi-automated execution standard.
7. `STD-DEV-021` — MVP layering, small core, and dependency execution standard.
8. `STD-DEV-022` — Internal MVP, client delivery, and monthly value control standard.
9. `STD-DEV-023` — Industry workflow-first and SME OS scope standard.
10. `STD-DEV-024` — AI collaboration and GitHub execution governance standard.

Earlier v1.4.1 to v1.4.3 patch files remain archived under `12_Archive` to preserve history without confusing AI tools about the current active rule set.

## Recommended Usage

```text
Markdown 分檔 = 正式原始文件
Word / PDF = 對外輸出或備份版本
GitHub Issues = 任務來源
Branch / Commit / Pull Request = 變更軌跡
Codex / Antigravity = 根據憲法與 MVP 文件執行開發
12_Archive = 歷史版本，不作為當前開發指令來源
```

## Top-Level Structure

```text
00_Admin                 文件索引、版本紀錄、manifest、v1.5.1 / v1.5.2 scope decision
01_Foundation            公司定位、開發憲法總覽、產品定位、WAS / SME OS 原則
02_Development_Standard  當前有效的開發流程、AI、GitHub、CR、MVP、交付治理標準
03_Client_Delivery       客戶交付、SOW、Blueprint、Handover、月費價值報告
04_Legal_Commercial      報價、付款、IP、PDPA、合約檢查
05_ISO_Ready             ISO-ready 控制對照與稽核證據
06_Grant_Ready           Grant-ready 證據包與案例模板
07_Templates             CR、Issue、AI Context Package、MVP、Workflow Blueprint、QA 等模板
08_Checklists            QA、部署、交接、PDPA、AI 執行、MVP readiness、workflow positioning checklist
09_Registers             CSV register：risk、change、lessons、third-party
10_Projects              專案 context：Optimaks OS、Aircon OS、ACRA Radar
11_Roadmap               憲法未來版本路線圖
12_Archive               已被 v1.5 融合或取代的歷史文件
```

## v1.5.2 Key Updates

- Keeps all v1.5.1 WAS / SME OS positioning updates.
- Adds `STD-DEV-024_AI_Collaboration_GitHub_Execution_Governance.md`.
- Adds `TPL-DEV-012_Pull_Request_Review_Template.md`.
- Adds `TPL-DEV-013_AI_Issue_Execution_Prompt_Template.md`.
- Adds `CHK-DEV-010_AI_GitHub_PR_Governance_Checklist.md`.
- Adds `.github/pull_request_template.md` and `.github/ISSUE_TEMPLATE/ai_execution_task.md`.
- Adds `00_Admin/V1.5.2_SCOPE_DECISION.md` to record the patch scope.
- Updates `FND-002_Development_Constitution_Overview.md`, `00_Admin/CHANGELOG.md`, `00_Admin/VERSION_HISTORY.md`, document index, file tree, and manifest.

## Important Governance Note

The current active version is **v1.5.2 AI Collaboration & GitHub Governance Patch**.

Files under `12_Archive` are historical references only. They may explain how the rules evolved, but they should not override active files in `01_Foundation`, `02_Development_Standard`, `03_Client_Delivery`, `07_Templates`, or `08_Checklists`.
