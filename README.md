# my-kb

`my-kb` 是一個面向 AI Agent 協作、交接與版本控管的知識庫專案。
這個專案不提供可執行的產品功能，而是作為團隊與 AI Agent 的共同工作基礎，讓不同角色能在同一個 GitHub repo 中，以一致的規則、交接格式與進度紀錄方式持續推進任務。

## 專案用途

- 集中管理 Agent 的共用規則與角色規範。
- 定義不同角色的責任邊界、工作方式與交接方式。
- 提供標準化交接模板，降低跨 Agent 續作成本。
- 透過 GitHub 版本控管保留每次變更的脈絡、決策與進度。

## 目前功能

- 共用規則文件：`AGENTS.md`
- 角色規則文件：
  - `.agents/planner.md`
  - `.agents/research.md`
  - `.agents/implementation.md`
  - `.agents/review.md`
- 交接模板：`.agents/handoff.md`
- 使用說明與索引：
  - `.agents/README.md`
  - `.agents/usage.md`
- 進度紀錄：`docs/PROGRESS.md`

## Quick Start

1. 先閱讀 `AGENTS.md`
2. 再閱讀 `.agents/README.md`，確認你要接手的角色
3. 依照 `.agents/usage.md` 與 `docs/PROGRESS.md` 開始工作
4. 結束時依 `.agents/handoff.md` 留下交接內容

## 啟動方式

本專案沒有應用程式或服務需要啟動。
使用方式很單純：

1. 先讀 `AGENTS.md`
2. 再讀自己對應的角色規則
3. 完成工作後依 `docs/PROGRESS.md` 與交接模板留下狀態

## 部署方式

本專案不需要傳統部署流程。
若要讓團隊或 AI Agent 持續使用，只要將 repo 維持在 GitHub 上，並確保規則文件與進度紀錄保持同步即可。

## 環境變數

目前沒有必須設定的環境變數。

若未來加入腳本、自動化流程或外部整合，請在此補充：

- 變數名稱
- 用途
- 預設值
- 是否為必要欄位

## 已知問題

- 目前沒有自動測試或自動驗證流程。
- 專案內容以文件與協作規則為主，尚未包含實際應用功能。
- 若多位協作者同時編輯，仍需依照 GitHub 的版本控管流程避免衝突。

## Repository Status

目前 repo 已包含可直接交接使用的規則文件、角色手冊與進度紀錄。
後續更新以文件優化、流程調整與交接品質提升為主。

## Contributing

若你要延伸這個 repo，建議先：

1. 讀 `AGENTS.md`
2. 讀 `.agents/README.md` 與對應角色規則
3. 先更新 `docs/PROGRESS.md` 再進行內容修改
4. 確保交接內容可讓下一位接手者直接延續

## Folder Structure

```text
.
├── AGENTS.md
├── README.md
├── docs/
│   └── PROGRESS.md
└── .agents/
    ├── README.md
    ├── handoff.md
    ├── implementation.md
    ├── planner.md
    ├── research.md
    ├── review.md
    └── usage.md
```

## How to Work With This Repo

- 先看共用規則，再看角色規則。
- 修改前先確認這次要動的檔案，避免影響範圍擴大。
- 修改後要寫清楚改動內容、影響範圍與下一步建議。
- 若任務已完成，請同步更新 `docs/PROGRESS.md`。
- 若需要交接，請使用 `.agents/handoff.md` 的格式。

## 下一步

- 讓角色規則更貼近實際工作情境。
- 為重要變更維持更完整的日期式進度紀錄。
- 若後續加入工具或腳本，再補齊啟動、部署與環境變數說明。
