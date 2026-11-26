# workflow-skills

Read this in [繁體中文](README.zh-TW.md).

Nine learned workflow skills for Muse — verification, approval, and delivery discipline, learned the hard way.

These are not tutorials. Eight of them are short rule sets written after a real mistake: a delivery made from memory, an approval claimed without checking, a build reported working that was never run. The ninth, apple-design, is a long-form distillation of Apple's WWDC design talks, not a mistake-driven rule set.

## Skills

- **approval-verification-shared-records** — Verify who actually approved what before calling a decision approved or writing it into a shared record.
- **check-real-source-before-delivery** — Check a generated image, map, characterisation or roster against its real or settled source before delivering it.
- **close-with-suggestion-and-options** — Close every completed work round with a named suggestion and labelled options.
- **apple-design** — Apple's approach to interface design and fluid, physical motion, translated for the web. Distilled from Apple's WWDC design talks, chiefly *Designing Fluid Interfaces* (WWDC 2018).
- **sync-all-claim-mirrors** — Update every copy of a corrected claim across a file, its notes, its history and its task list.
- **verify-interactive-build-by-running-it** — Run an interactive build through its real load and interaction paths before delivery.
- **verify-shared-artifact-delivery** — Recount and re-read a shared board, map, or artifact after an edit.
- **avoid-duplicate-shared-channel-reply** — Reply once in a shared group channel by checking just before posting whether another reply already covers the event.
- **verify-official-list-item-by-item** — Check every item in an official or brochure list against its primary source.

## Use

Copy any skill folder into your own skills directory (e.g. `~/.claude/skills/` or your project's skills folder). Each skill is one `SKILL.md` with frontmatter (`name` + `description`).

## Related projects

Three parts of one workflow — rules, then tiers, then a paper trail:

- [workflow-skills](https://github.com/kttcat/workflow-skills) — the rules: this repo.
- [tiered-review](https://github.com/kttcat/tiered-review) — the tiers: three-tier approval framework for AI agents.
- [sqlite-audit-log](https://github.com/kttcat/sqlite-audit-log) — the paper trail: append-only SQLite audit log.

## License

MIT — see [LICENSE](LICENSE).
