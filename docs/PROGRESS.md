# Progress

## 2026-06-20

- 完成建立 Agent 共用規則與角色規則的基礎架構。
- 補上 GitHub 版本控管與 AI 交接導向的使用說明。
- 新增專案首頁 `README.md`，說明用途、目前功能、啟動方式、部署方式、環境變數、已知問題與下一步。

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

### 決策

- 這個 repo 目前定位為 Agent 規則與交接知識庫，不描述不存在的應用程式功能。
- 使用 `docs/PROGRESS.md` 作為日期式進度紀錄，方便 AI 接手時快速掃描。
- 把修改前後的工作流程寫進共用規則，確保後續 Agent 都能照一致方式協作。

### 目前卡點

- 這個環境目前沒有可直接使用的 `git` 指令，因此尚未完成 commit 與 push。

### 下次接手先看

- `AGENTS.md`
- `README.md`
- 最新一筆 `docs/PROGRESS.md`
- `.agents/usage.md`

