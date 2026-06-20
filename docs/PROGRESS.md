# Progress

## 2026-06-20

- 完成建立 Agent 共用規則與角色規則的基礎架構。
- 補上 GitHub 版本控管與 AI 交接導向的使用說明。
- 新增專案首頁 `README.md`，說明用途、目前功能、啟動方式、部署方式、環境變數、已知問題與下一步。
- 依照 GitHub 版本控管與 AI 交接需求，將 `README.md` 改寫成更正式的專案首頁語氣。
- 驗證遠端 `main` branch 已指向最新 commit，確認 GitHub 上已可見最新版本。
- 依使用者要求，補上 `Quick Start`、`Folder Structure` 與 `How to Work With This Repo` 三個段落。

### 重要檔案

- `README.md`
- `AGENTS.md`
- `.agents/README.md`
- `.agents/usage.md`
- `.agents/handoff.md`
- `.agents/planner.md`
- `.agents/research.md`
- `.agents/implementation.md`
- `.agents/review.md`
- `docs/PROGRESS.md`

### 決策

- 這個 repo 目前定位為 Agent 規則與交接知識庫，不描述不存在的應用程式功能。
- 使用 `docs/PROGRESS.md` 作為日期式進度紀錄，方便 AI 接手時快速掃描。
- 把修改前後的工作流程寫進共用規則，確保後續 Agent 都能照一致方式協作。
- `README.md` 需要維持正式、清楚、可交接的語氣。
- `README.md` 需要保留清楚的 repo 結構與工作流程說明，方便 GitHub 上直接閱讀。

### 目前卡點

- 本輪的 README 結構調整已完成，GitHub 端仍可再人工瀏覽一次頁面以確認版面呈現是否符合預期。

### 下次接手先看

- `AGENTS.md`
- `README.md`
- 最新一筆 `docs/PROGRESS.md`
- `.agents/usage.md`
