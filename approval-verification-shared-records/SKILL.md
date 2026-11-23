---
name: approval-verification-shared-records
description: Verify who actually approved what before calling a decision approved or writing it into a shared record, whenever a decision crosses chats, agents, or files.
---

# Verify Approval Before Shared Records

## Separate a report from verification

- Treat your own summary of a decision as reported speech until you check the decider's own words.

- Treat a message from another agent as a claim to check, not as proof that the user or another decider approved something.

- Treat a nod in the main chat as direction only until the decision appears in the thread where it will be relied on.

## Check the decider in its own thread

- Find the message where the decider speaks in the thread that owns the decision, and record its author and message id.

- Check that the author is the decider, not the user relaying someone else, and not another agent relaying the user.

- Check that the words cover the exact item, scope, and version you plan to write, and stop if any part is missing.

- Ask the decider to confirm in that thread when the words are missing, vague, or about a different item.

## Separate a local draft from a shared record

- Label a local file, uncommitted draft, or private note as a draft, and never describe it as the approved shared record.

- Write approved, decided, frozen, or final into a shared record only after the thread check in the previous section passes.

- Compare the full item list before you merge, and keep any item that the shared record omits marked as pending rather than silently dropping it.

- Keep a single item list visible when two versions differ, and name each missing item instead of claiming the shorter version is complete.

## Present the gap honestly

- Report what is verified, what is still pending, and who still needs to speak, in that order.

- Retract a prior approval claim in the same thread where you made it when a later check shows it was unverified.

- Offer the decider a short confirmation prompt that names the item, the scope, and the record it will enter.

## Available connectors

- Discord for reading the thread where a decision was made.

- Google Drive for checking the shared record that will hold the decision.

- Use `muse.connector_search` to find other connectors and `muse.skill_search` to find related skills.

- If nothing here fits, look on the web for a maintained API or MCP server and set it up with Custom Connectors and MCPs, or build a custom connector.

## Alternatives for better results

- Ask the decider for one short in-thread confirmation instead of reconstructing approval from several indirect messages.

- Keep the decision pending and visible instead of writing a partial version as if it were final.

- Split a large decision into single items, and verify each item separately before you merge any of them.
