# AI Assisted Development Workflow

| Field | Value |
|---|---|
| Document Code | STD-DEV-002 |
| Version | v1.3 |
| Effective Date | 2026-05-13 |
| Owner | Optimaks Pte Ltd |
| Status | Active |
| Purpose | Define ChatGPT, Codex, Antigravity, Claude, and Gemini roles. |

---


## Official AI Development Tooling

Optimaks currently uses the following primary AI-assisted development tools:

1. ChatGPT
2. Codex
3. Antigravity

Codex and Antigravity are the main development tools. Claude and Gemini are model options inside Antigravity and are **not** treated as separate standalone development tools in this workflow.

## Tool Roles

### ChatGPT

Used for:

- Change Request drafting
- GitHub Issue preparation
- Architecture discussion
- Documentation
- Prompt writing

### Codex

Used for:

- Main implementation agent
- Repository-level changes
- Bug fixing
- Refactoring
- PR / code change preparation
- Following GitHub Issue requirements

### Antigravity

Used for:

- AI IDE
- UI iteration
- Frontend review
- Code exploration
- Interactive debugging support
- Comparing implementation approaches

### Models inside Antigravity

- Claude model: requirement interpretation, architecture review, refactoring analysis, long-context review.
- Gemini model: UI ideas, multimodal understanding, fast option comparison, Google ecosystem support.

## AI Tooling Workflow

```text
GitHub Issue / Change Request
        ↓
Codex
主要工程實作 / Bug Fix / Refactor
        ↓
Antigravity
AI IDE 審查 / UI 調整 / 測試輔助
        ↓
Antigravity 內部模型
   ├── Claude：需求理解 / 架構審查 / 重構分析
   └── Gemini：UI 發想 / 多模態 / 快速方案比較
        ↓
Vercel Preview / Staging
        ↓
手機 + 桌機測試
        ↓
Merge / Deploy
```

## AI Usage Rules

1. AI can propose solutions, but implementation must follow GitHub Issue and Change Request.
2. AI can modify code, but the change must go through Preview and testing.
3. AI cannot directly decide production deployment.
4. AI-generated changes must have commit, diff, testing steps, and rollback awareness.
5. Database/Auth/Permission changes require special review.


---

## v1.5.2 Governance Addendum

This workflow is strengthened by `STD-DEV-024`, which defines one issue / one branch / one PR, AI tool boundaries, and human review requirements for AI-generated code.
