# Optimaks Document Library v1.3

This repository folder is the official GitHub-ready document library for Optimaks development governance.

本文件庫將原本的 **Optimaks Development Constitution v1.3** 拆成分章節 Markdown 文件，方便：

1. GitHub 版本比對
2. Codex / Antigravity 分段讀取
3. Change Request 影響範圍管理
4. 客戶交付文件與內部制度文件分離
5. ISO-ready / grant-ready 證據整理

## Recommended Usage

```text
Markdown 分檔 = 正式原始文件
Word / PDF = 對外輸出或備份版本
GitHub Issues = 任務來源
Branch / Commit / Pull Request = 變更軌跡
```

## Top-Level Structure

```text
00_Admin              文件索引、版本紀錄、manifest
01_Foundation         公司定位、開發憲法總覽、核心原則
02_Development_Standard 開發流程、AI、GitHub、CR、手機、部署、QA
03_Client_Delivery    客戶交付、SOW、Blueprint、Handover、維護報告
04_Legal_Commercial   報價、付款、IP、PDPA、合約檢查
05_ISO_Ready          ISO-ready 控制對照與稽核證據
06_Grant_Ready        Grant-ready 證據包與案例模板
07_Templates          CR、Issue、Codex prompt、Mobile capture、QA report
08_Checklists         QA、部署、交接、PDPA、手機測試
09_Registers          CSV register：risk、change、lessons、third-party
10_Projects           專案 context：Optimaks OS、Aircon OS、ACRA Radar
```

## v1.3 Key Updates

- 新增 Mobile-Assisted Development Workflow。
- 手機流程改為以工具角色劃分，而非白天/晚上作息劃分。
- 修正 AI 工具架構：正式主工具為 Codex + Antigravity。
- Claude / Gemini 定義為 Antigravity 內部模型選項，不作為獨立開發工具。
- 強化 GitHub Issue、Change Request、Staging / Preview / Production、文件更新流程。

## How to Update This Library

```text
Create branch
  ↓
Update affected Markdown files
  ↓
Update CHANGELOG.md
  ↓
Update DOC-INDEX-001_Document_Index.md if adding/removing files
  ↓
Commit
  ↓
Push
  ↓
Review diff
  ↓
Merge
```
