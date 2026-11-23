---
name: sync-all-claim-mirrors
description: Update every copy of a corrected claim across a file, its notes, its history and its task list before calling the correction complete.
---

# Sync every mirror of a claim

## List every mirror before you edit

- List every place that states the claim before you change any copy of it.

- Include the main text and any notes section and history annotation and task list entry and summary that repeats the same claim.

- Treat a place you have not listed as a place that will stay stale.

## Update every mirror in one pass

- Change every listed mirror in the same editing pass instead of fixing one place and returning later for the next.

- Keep the wording of the corrected claim the same across mirrors unless a mirror needs a shorter form and the shorter form still states the same fact.

- Leave a mirror unchanged only when you have a stated reason and you name that mirror as an exception in the delivery.

## Grep and declare completion only when mirrors agree

- Search the whole artifact and its task list for the old wording and for the key phrase of the old claim after the edit.

- Fix any remaining old copy you find instead of reporting the correction as complete.

- Report the correction as complete only when the search shows no old copy or when every remaining old copy is named as an explicit exception.

- Run the recount check separately when the correction changes a number or a status and keep that check outside this mirror check.

## Available connectors

- Use `muse.connector_search` to find other connectors and `muse.skill_search` to find related skills.

- If nothing here fits, look on the web for a maintained API or MCP server and set it up with Custom Connectors and MCPs, or build a custom connector.

## Alternatives for better results

- Ask the user which mirror is authoritative when two mirrors disagree and neither one is clearly the newer one.

- Reduce the number of mirrors for a claim when one copy can serve as the single source and the other places can point to it.
