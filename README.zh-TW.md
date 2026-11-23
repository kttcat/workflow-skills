# workflow-skills

English 版本請見 [README.md](README.md)。

九支從實戰中學來的工作流程 skills，給 Muse 用——查證、批准、交付的紀律，都是吃過虧才寫下來的。

這不是教學文。每支 skill 都是一組短規則，寫在一次真實失誤之後：憑記憶交付、沒查證就說已批准、沒跑過就說 build 沒問題。

## Skills

- **approval-verification-shared-records** — 說一個決定已批准、寫進共享紀錄之前，先查證到底是誰批准了什麼。
- **check-real-source-before-delivery** — 交付生圖、地圖、角色設定或名單之前，先拿去對真實來源或定案。
- **close-with-suggestion-and-options** — 每輪工作做完，用一個具名建議加可點選的選項收尾。
- **apple-design** — Apple 的介面設計與流暢、物理感動效做法，轉寫成網頁版。整理自 Apple WWDC 設計講座，主要是《Designing Fluid Interfaces》（WWDC 2018）。
- **sync-all-claim-mirrors** — 一個說法被更正後，把檔案、筆記、歷史紀錄、任務清單裡的每一份副本都同步更新。
- **verify-interactive-build-by-running-it** — 互動成品交付前，先走一次它真實的載入與互動路徑。
- **verify-shared-artifact-delivery** — 共享的看板、地圖或成品改完後，重新數一次、重新讀一次再交付。
- **avoid-duplicate-shared-channel-reply** — 在共享群組頻道只回一次，發文前先確認是不是已經有回覆講過同一件事。
- **verify-official-list-item-by-item** — 官方或宣傳清單裡的每一項，逐項拿去對原始來源。

## 使用方式

把任一 skill 資料夾複製到你自己的 skills 目錄（例如 `~/.claude/skills/` 或專案的 skills 資料夾）。每支 skill 就是一個帶 frontmatter（`name`＋`description`）的 `SKILL.md`。

## 授權

MIT — 見 [LICENSE](LICENSE)。
