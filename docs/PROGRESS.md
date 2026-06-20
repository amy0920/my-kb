# Progress

## 2026-06-20

- 完成建立 Agent 共用規則與角色規則的基礎架構。
- 補上 GitHub 版本控管與 AI 交接導向的使用說明。
- 新增專案首頁 `README.md`，說明用途、目前功能、啟動方式、部署方式、環境變數、已知問題與下一步。
- 依照 GitHub 版本控管與 AI 交接需求，將 `README.md` 改寫成更正式的專案首頁語氣。
- 驗證遠端 `main` branch 已指向最新 commit，確認 GitHub 上已可見最新版本。
- 依使用者要求，補上 `Quick Start`、`Folder Structure` 與 `How to Work With This Repo` 三個段落。
- 將 `.agents/usage.md` 擴寫成更完整的 Agent 工作手冊，補上開始前、工作中、結束時、交接標準與常見錯誤。
- 進一步將 `README.md` 文字整理成更正式的專案首頁語氣。
- 再補上 `Repository Status` 與 `Contributing` 段落，讓 README 更接近正式 GitHub 專案頁的結構。
- 為 `README.md` 補上 `License` 與 `Ownership` 收尾段落。
- 將 `.agents/README.md` 改成更像目錄首頁的導覽版面，加入快速入口與角色文件表格。
- 依需求新增 `.gitignore` 與 `SECURITY.md`，明確避免私密金鑰、API Key、憑證與環境檔被提交到 GitHub。
- 依需求再調整 `.gitignore`，加入常見編輯器暫存檔與備份檔規則，並在 `README.md` 補上安全提醒。

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
- `.gitignore`
- `SECURITY.md`

### 決策

- 這個 repo 目前定位為 Agent 規則與交接知識庫，不描述不存在的應用程式功能。
- 使用 `docs/PROGRESS.md` 作為日期式進度紀錄，方便 AI 接手時快速掃描。
- 把修改前後的工作流程寫進共用規則，確保後續 Agent 都能照一致方式協作。
- `README.md` 需要維持正式、清楚、可交接的語氣。
- `README.md` 需要保留清楚的 repo 結構與工作流程說明，方便 GitHub 上直接閱讀。
- `.agents/usage.md` 需要維持可直接交接的手冊語氣，避免過度抽象。
- README 可加入簡短的專案狀態與協作方式區塊，以符合 GitHub 專案頁常見結構。
- `.agents/README.md` 適合用更明確的導覽結構，讓新接手者快速找到入口。
- `.gitignore` 與 `SECURITY.md` 可作為預設防護，降低把敏感資訊提交到 GitHub 的風險。
- `.gitignore` 可補上常見編輯器暫存檔與備份檔，減少雜訊進入版本控管。

### 目前卡點

- 本輪的 README 與工作手冊調整已完成，GitHub 端仍可再人工瀏覽一次頁面以確認版面呈現是否符合預期。

### 下次接手先看

- `AGENTS.md`
- `README.md`
- 最新一筆 `docs/PROGRESS.md`
- `.agents/usage.md`
