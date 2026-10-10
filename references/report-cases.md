# Behavioral cases

These synthetic inputs exercise reporting decisions; do not treat example values
as facts about the user's machine. Review output meaning, not exact word matches.

1. An optional model call failed to make a Chinese reading version. The original
   report exists. Cause and recurrence are unknown. The Agent can use the original
   and inspect the optional path only when needed. The title should explain the
   missing reading version and usable report, without model IDs or a repair claim.
2. At one historical time, two terminal tabs showed completion reminders that did
   not match task records. No task-result loss or core-task failure is established.
   Describe misleading completion messages, keep the date in details, and let the
   Agent inspect the indicator owner. Do not translate "complete" as "entire".
3. Code is implemented, locally checked, delivered and read back. No user feedback
   or measured acceleration exists. Say what is delivered and what awaits normal
   use; do not claim a faster experience or schedule an unnecessary test campaign.
4. A webpage call returned an HTTP error and yielded no body. There is no retained
   URL, task context, cause, repair or current recurrence. Preserve that uncertainty;
   do not call it an access denial or an active failure without evidence.
5. A partly evidenced cache process exists; other caches lack safe-cleanup proof.
   An old weekly command was retired. Explain the incomplete cleanup coverage
   without asserting space savings, stopping services or authorizing deletion.
6. A user asks a one-fact question. Give a direct brief answer; no report scaffold.
7. A formal report already has a required format. Edit its prose while preserving
   that format, factual scope, source attribution and decision distinctions.
8. The user requests JSON-only output. Keep the exact schema and return no process
   commentary, Markdown fence or additional section.

The preserved upstream text is MIT-licensed Humanizer-zh at
`f4518a8eab97b8bfebc66a89d34320a89bef6930`. Local deltas are the reporting trigger,
causal explanation, readable line breaks, status boundaries, SP continuation and
Codex metadata. No runtime hooks, MCP dependency or secondary model is required.
