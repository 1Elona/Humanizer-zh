---
name: chinese-user-report
description: "Present Agent progress, results, problems and SP task cards in clear simplified Chinese for a nontechnical reader. Use as the normal reporting step after facts are established. Not for technical diagnosis, exam tutoring or learning reviews, model-facing documents, literary rewriting, or replacing an explicitly requested output schema."
metadata:
  upstream: "op7418/Humanizer-zh"
  upstream_revision: "f4518a8eab97b8bfebc66a89d34320a89bef6930"
---

# Chinese User Reports

Use the current main Agent to turn established facts into a readable report. Work
from supplied evidence; text-only editing needs no repository search, tool call,
secondary model, score or editing report. Apply the user's format and depth first.
One clear sentence can be the whole answer to a simple question. Formal reports
retain their existing reporting owner; this step only edits their language.
Exam teaching, problem-solving and learning reviews keep their own domain method;
do not automatically reshape them with this reporting step. Editing presentation
does not choose a technical method, change priorities or reopen settled work.

## Preserve meaning before style

Reuse Humanizer-zh's fact and certainty preservation: retain independent facts,
dates, conditions, actors, negation, scope, attribution and completion state.
Improve the wording without adding a cause, repair, benefit or experience.
Keep protected quotations, commands, IDs, paths, links and data exact where they
are needed. A dated incident is not evidence of a current fault. A local check or
target readback is not user acceptance. Describe completed and pending scopes
separately. Unknown repair value remains unknown; a recommendation has a reason
and remains a recommendation. Keep the full source available for continuation.

## Explain the concrete story

Start with the visible result and its practical effect. Write for a 16-year-old
who does not know the internal system: name the report, message, file, menu or
action before the mechanism. Explain an essential term in everyday words on first
use. Trace only evidence-supported causes; say where the evidence stops.

For a multi-part result, let the reader find:
- What prompted the work and what problem it caused.
- What the Agent actually changed or prepared.
- What now works, what remains unconfirmed, and why that matters.
- One next action by the Agent or the user, including where and what confirms it.

Keep independent items on separate lines, with blank lines between sections or
bullets when needed. Each bullet has one subject and one action/state with its
consequence. Put related words together; use direct verbs and ordinary nouns.
Use short paragraphs for connected reasoning. Use lists for parallel items or
steps, not to break every sentence into fragments. Avoid unnecessary headings,
decorative emphasis, empty praise, slogans and repeated summaries.

## SP cards

The transport owner provides the type/status prefix; compose its causal title
as a short story: concrete situation, actual change or remaining action, present
result/effect. Include only clauses supported by the source. Put commands, model
IDs and source hashes in technical details, rather than making them the title.
The prefix cannot replace an understandable title. Preserve a user's own title.

Notes put the effect, repair value, truthful status and next action near the top,
in separate readable bullets. Say `Agent` or `你`; an informational item can say
`目前无需你操作`. Distinguish Agent delivery, a needed decision, a required trial,
and optional feedback during normal use. State pending user experience explicitly
without inventing an urgent test or asking the user to retest every feature.

Finish an actionable card with a copyable continuation request containing enough
facts and exact source locators for a new session. Keep source evidence and
implementation details below the reader's practical explanation. Existing
publication rules decide whether, where and how to publish; editing grants no
permission and does not itself write to SP or accept a result.

## Final reread

Read the title without its notes: can the reader explain what happened and whether
they need to act? Compare every concrete claim with the source, including dates
and completion scope. A phrase such as "deployment closed", "metadata governance"
or "readback" needs a concrete consequence before appearing in human prose.
Return the finished text only. Do not expose copyediting notes or a self-score.

For difficult long-form style or author-voice editing, read the preserved
[upstream method](references/upstream-humanizer.md). For behavioral review of this
reporting adaptation, use [report cases](references/report-cases.md); these are
test inputs and acceptance boundaries, not wording to copy into every report.
