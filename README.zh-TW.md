# workflow-skills

English 版本請見 [README.md](README.md)。

九支跟 Muse 搭配用的工作流程 skills，講的是查證、批准、交付的紀律——八支是吃過虧之後才寫下來的。

這不是教學文。其中八支 skill 背後都是一次真實失誤：憑印象交件、沒查證就說人家批准了、沒跑過就說 build 沒問題。第九支 apple-design 是 Apple WWDC 設計講座的長篇整理，不是失誤驅動的短規則。

## Skills

- **approval-verification-shared-records** — 要說一個決定已經批准、要寫進共享紀錄之前，先查清楚到底是誰批准了什麼。
- **check-real-source-before-delivery** — 生圖、地圖、角色設定、名單交出去之前，先拿去跟真實來源或定案對一次。
- **close-with-suggestion-and-options** — 每輪工作收尾時，給一個具名的建議，再加幾個可以點的選項。
- **apple-design** — Apple 的介面設計和流暢、帶物理感的動效，轉成網頁的做法。整理自 Apple WWDC 的設計講座，主要是《Designing Fluid Interfaces》（WWDC 2018）。
- **sync-all-claim-mirrors** — 一個說法被更正之後，檔案、筆記、歷史紀錄、任務清單裡的每一份副本都要一起改。
- **verify-interactive-build-by-running-it** — 互動成品交出去之前，先照它真實的載入和互動路徑跑一遍。
- **verify-shared-artifact-delivery** — 共享的看板、地圖或成品改完之後，重新數一遍、重新讀一遍再交。
- **avoid-duplicate-shared-channel-reply** — 在共享群組頻道裡只回一次；發文前先看一下，是不是已經有人回過同一件事。
- **verify-official-list-item-by-item** — 官方或宣傳清單上的每一項，都要逐項去對原始來源。

## 使用方式

挑一支 skill，把整個資料夾複製到你自己的 skills 目錄（例如 `~/.claude/skills/` 或專案裡的 skills 資料夾）。每支 skill 就是一個 `SKILL.md`，前面帶著 frontmatter（`name`＋`description`）。

## 相關專案

同一套流程的三個部分——規範、分級、留痕：

- [workflow-skills](https://github.com/kttcat/workflow-skills) — 規範：這個 repo。
- [tiered-review](https://github.com/kttcat/tiered-review) — 分級：AI agent 三級審查框架。
- [sqlite-audit-log](https://github.com/kttcat/sqlite-audit-log) — 留痕：只追加的 SQLite 稽核紀錄。

## 授權

MIT — 見 [LICENSE](LICENSE)。
