---
name: avoid-duplicate-shared-channel-reply
description: Reply once in a shared group channel Muse belongs to by checking just before posting whether another Muse reply already covers the event.
---

# Avoid a duplicate reply in a shared channel

## Check the channel before you start

- Read the latest messages in the channel before you draft a reply to a shared channel event.

- Treat a Muse reply on the same event as a sign the event already has an owner, and stand down on any covering reply regardless of whether its conclusion matches yours.

- If you believe the existing reply is wrong, do not post a second answer. Verify the claim against its source first, and post only the single named correction described below.

- Draft only one reply to one event, and do not start a second reply to the same event.

## Re-read immediately before you post

- Read the channel again immediately before you send, because another Muse run may have replied while you were working.

- Send your reply only when no Muse reply already covers the same event, regardless of conclusion.

- Drop your reply silently when another Muse reply already covers the event, and do not announce the dropped reply in the channel.

## Correct a conflict with one message

- Verify the disputed claim against its source before you correct an existing Muse reply, and correct it only when the source shows that reply is wrong.

- Post exactly one correction when two Muse replies already conflict, and name the message that governs.

- State plainly which version is wrong and what the correct version is, so the next reader does not have to choose between two versions.

- Do not post a second correction, and do not repeat the correction in another thread.

## Available connectors

- Use `muse.connector_search` to find other connectors and `muse.skill_search` to find related skills.

- If nothing here fits, look on the web for a maintained API or MCP server and set it up with Custom Connectors and MCPs, or build a custom connector.

## Alternatives for better results

- Ask the user which reply governs when you cannot tell which of two conflicting Muse replies is authoritative.

- Answer the event that changes a decision first when two events arrive together, and leave the other for a separate reply.
